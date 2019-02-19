# mjml-boilerplate

mjml-boilerplate is an opinionated software stack and file structure for developing HTML emails.

## Installation
There’s just six steps you get you started. In the Terminal…

1. Go to where you want to save your new project e.g.
```
$ cd ~/Sites
```

2. Paste the following code
 ```
$ echo What’s your project called? && read dir && mkdir "$dir" && curl -L https://github.com/jonathonoates/mjml-boilerplate/tarball/master > tmp.tar.gz && tar fxz tmp.tar.gz -C "$dir" --strip-components=1 && rm tmp.tar.gz
```

3. Give your project a name e.g. `my-new-email`
 ```
What’s your project called?
my-new-email
```

4. You’ve a new folder for your project 😉 Go into it
```
$ cd my-new-email
```

5. Install the devDependencies
```
$ npm install
```

6. Fire it up 🔥
```
$ npm start
```

## Usage

1. Given the above installation, go into your projects folder e.g.
```
$ cd ~/Sites/my-new-email
```

2. Start everything up again
```
$ npm start
```
