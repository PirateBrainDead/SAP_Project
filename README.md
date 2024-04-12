# Sap Project Secure

This is my Ruby On Rails Project. It emphasizes secure coding practices.

## Getting Started

These instructions will help you set up and run the project on your local machine for development and testing purposes.

### Downloads

Before installing the software, make sure you have the following:

#### For Windows:
* Ruby Installer: [Ruby Installer](https://rubyinstaller.org/) (I used version 3.1.2)
* SQLite: [SQLite](https://www.sqlite.org/index.html) (I used version 3.39.4)

#### For Mac and other OS:
Please follow this guide: [Ruby Downloads](https://www.ruby-lang.org/en/downloads/)

### Installation

After installing Ruby, follow these commands to install Rails:

1. Open up a command terminal (cmd).
2. Check the version of Ruby and RubyGems using:

```
$gem -v
```
```
$ruby -v
```

3. Install Rails using:


```
$gem install rails
```

After installation, verify the Rails version (I'm using Rails 7.0.4.3):

```
$rails -v 
```

## Usage

To run the application:

1. Download both the secure and insecure projects from GitHub.
2. Navigate to the project directory in your terminal.
3. Run `bundle install` to install all required gems:

```

$ bundle install
```

4. Migrate pending migrations:

```
$ rails db:migrate
```


## Seed the Application

Seed the application with users using:

```
$ rake seed_users
```
This will give you admin users and normal users 


This will generate both admin and normal user accounts.

### User Details

Admin Users:
- Username: jenny@gmail.com
- Password: pancake

Normal Users:
- Username: kev@gmail.com
- Password: coffeecake

- Username: slvy@gmail.com
- Password: cakefrost

### Run Locally

You can run the application either on localhost or through a local IP.

To run it on localhost, simply type:


```
$ rails server
```

This will start the Rails server, accessible at http://localhost:3000.

To run through local IPv4:

1. Find your IPv4 address:

```
$ ip config
```

2. Run the server using (port 3000):


```
$ rails s -b 0.0.0.0
```

Access your application by opening a web browser and typing your IP along with the port (e.g., 10.198.12.106:3000). Note that your IPv4 address will be different.

### Branches

- Secure
- Insecure

## Additional Documentation and Acknowledgments

For any installation issues, please refer to the Ruby on Rails guide documentation:

* [Ruby Downloads](https://www.ruby-lang.org/en/downloads/)
* [Ruby on Rails Guide](https://guides.rubyonrails.org/getting_started.html)
