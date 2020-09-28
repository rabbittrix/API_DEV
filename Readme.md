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
            