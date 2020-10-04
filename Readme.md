# MongoDB Connection
mongodb+srv://test1234:<password>@test1234.xdo2l.mongodb.net/apidev?retryWrites=true&w=majority

# Please use a valid URL with HTTP or HTTPS (regex)
/https?:\/\/(www\.)?[-a-zA-Z0-9@:%._\+~#=]{1,256}\.[a-zA-Z0-9()]{1,6}\b([-a-zA-Z0-9()@:%_\+.~#?&//=]*)/,

# Please use a valid email (regex)
/^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/
## or
/^\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+$/

# Error Refused to execute inline script because it violates the following Content Security Policy directive

// Set Security headers
app.use(helmet({ contentSecurityPolicy: false }));

# SEEDER
node seeder -i (create BD)
node seeder -d (destroy BD)

# .env configuration
NODE_ENV=development
PORT=5000

MONGO_URILOCAL=mongodb://localhost/apidev
MONGO_URI=mongodb+srv://test1234:<password>@test1234.xdo2l.mongodb.net/apidev?retryWrites=true&w=majority

GEOCODER_PROVIDER=mapquest
GEOCODER_API_KEY=<Key>

FILE_UPLOAD_PATH= ./public/uploads
MAX_FILE_UPLOAD=1000000

JWT_SECRET=<Key>
JWT_EXPIRE=30d
JWT_COOKIE_EXPIRE=30

SMTP_HOST=smtp.gmail.com
SMTP_PORT=2525
SMTP_EMAIL=794c138f087a26
SMTP_PASSWORD=<password>
FROM_EMAIL=noreply@gmail.com
FROM_NAME=<Any_Name>