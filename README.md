# Makos Get In My Car™ (WIP)

### Basic setup
You'll need this to work with AWS S3
- Download and unzip the code in this repo
- Create file <user>/.aws/credentials (notice the lack of a file extension)
- Open it with Notepad, and paste the following into it:

```
[default]
aws_access_key_id = <ACCESS_KEY>
aws_secret_access_key = <SECRET_KEY>
```

- Replace the angle brackets with the data William sent you

I am hoping you have already [installed Node.js](https://nodejs.org/en/download/) and have [any code editor that's not vim](https://code.visualstudio.com/). If not, do that before proceeding.

### Node.JS Setup
This will be the functional part of the code. 
- Open the console. (you can do it by typing `cmd` in the Windows search bar)
- Type `color 0A`. This is an important step and you should not skip it under any circumstances
- Navigate to the folder the project is in. If you have it open in File Explorer, you can just click the down arrow in the top bar and copy what comes up.
    - After you have the address, type `cd` followed by the address.
- Type `npm install` to download all appropiate directories
- Open `main.js` from the code you downloaded earlier
- Do your thing. With the default code, "TEST" will be written to `test2.json` in bucket `carpool-project`. If you don't know what any of that means, you're not alone.


<img src="https://i.giphy.com/media/Bap9PFewF20es/giphy.webp" width=200>
