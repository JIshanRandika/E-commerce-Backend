
### Environment Variables
```bash
# Database connection string
MONGO_URI="mongodb://localhost:27017/your-database-name"

# Frontend URL (adjust if needed)
ORIGIN="http://localhost:3000"

# Email credentials for sending password resets and OTPs
EMAIL="your-email@example.com"
PASSWORD="your-email-password"

# Token and cookie expiration settings
LOGIN_TOKEN_EXPIRATION="30d"  # Days
OTP_EXPIRATION_TIME="120000"  # Milliseconds
PASSWORD_RESET_TOKEN_EXPIRATION="2m"  # Minutes
COOKIE_EXPIRATION_DAYS="30"    # Days

# Secret key for jwt security
SECRET_KEY="your-secret-key"

# Environment (production/development)
PRODUCTION="false" # Initially set to false for development
```




### Data seeding
- Run the seeding script: `npm run seed` ( This script executes the `seed.js` file within the `seed` subdirectory equivalent to running `node seed/seed.js` )

### Login with demo account
```bash
  email: ishan@gmail.com
  pass: helloWorld@123
```
