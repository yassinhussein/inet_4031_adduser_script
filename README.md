User Creation Script
Python script automates the creation of user accounts and groups
## Program Operation
1. Prepare user data in `create-users.input` with this format: `username:password:last name:first name:groups`.
2. Run the script with:
   ```bash
   sudo ./create-users.py < create-users.input
verfy passwd / groups
