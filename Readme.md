# # Hire-ME

<img src="screenshots/HireMe.png" width="800">

### DBMS Mini-project: Recruitment Management System.💫✨

# Features

- **_Python + MYSQL using mysql.connector library_**
- **_Recruiter and Client Panel_**
- **_Beautiful UI using tkinter_**

### :rocket:Glimpse :dizzy::dizzy:<br><br>

<img src="screenshots/001_login.png" width="500">
<img src="screenshots/006_login_recruiter_mainscreen.png" width="500">
<img src="screenshots/011_client_availablejobs.png" width="500">

## Setup

##### Clone the repository

```bash
git clone https://github.com/nh037/Hire-Me.git
```

##### Move to the desired folder

```bash
cd Hire-ME
```

##### To install the dependencies, simply write

```bash
pip install -r requirements.txt
```

##### Make sure MYSQL is running on your System . Now move to `creds.py` inside modules folder and replace the value of `user_pwd`

```
 user_pwd = "your mysql password"
```

##### Now we're almost done so to create the required schema in your machine simply run

```bash
python db_init.py
```

##### After setting up the schema, to run simply write

```bash
python main.py
```

---

## Future-Scope

- More Features can be added like we can make Resume on it and can share to nearby recruiters
- Super-User(Admin) Panel For Future Features.
- many more ...
