# reddit_command_line_interface
# Description 

Reddit Cli is a reddit command line interface which could be used to browse and read data from reddit.

## Installation

Reddit-CLI requires python 3 or above. Get it from [here](https://www.python.org/downloads/windows/)

1. Clone repository to your Desktop.

2. Download and Extract.

3. Open command prompt and cd to the reddit-cli directory:

4. For installing required packages.
```sh
pip install -r requirements.txt
```
5. Create credential.json with following format.
```sh
{"client_id":"<client_id>", "client_secret":"<client_secret>", "user_agent":"('platform:''com.package.reddit:v1.0''(by /u/username)')"}
```

6. You can get your client_id and client_secret by creating an app through [this link](https://www.reddit.com/prefs/apps).
## Usage
To run the python script run the following command in terminal after finishing the installation process and configuring ```credentials.json``` file.
```bash
 python -m reddit
```
Follow the instructions on the terminal screen afterwards.
## Features
The features of our Reddit CLI are as follows:-
* Find the subreddits followed by our user.
* Get the list of users blocked by our user.
* Browse subreddit posts

