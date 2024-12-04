# WomenInSwift-Job-Board &emsp; [![Build Project](https://github.com/WomenInSwift/WomenInSwift-Job-Board/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/zero-to-mastery/WomenInSwift-Job-Board/actions/workflows/build.yml)

A place for Apple developers from the [**WomenInSwift**](https://womeninswift.io/?utm_source=github&utm_medium=WomenInSwift-Job-Board) to show recruiters that they are available for hire. Feel free to contribute and improve this in any way you see fit.

Link to the webpage: [**WomenInSwift JOB Board**](https://womeninswift.github.io/WomenInSwift-Job-Board/).

### How to run the project in your local machine

- `git clone https://github.com/zero-to-mastery/WomenInSwift-Job-Board.git`

- `cd WomenInSwift-Job-Board`

- `npm ci`

- `npm start`

### How to add your name to the list

Note: **You will first need to make a fork of the project!**

![fork image](https://docs.github.com/assets/cb-79331/mw-1440/images/help/repository/fork-button.webp)

If you are unclear on how the GitHub workflow works, you can check the [Make a Pull Request guide](https://makeapullrequest.com/).

---

To add your name to the list, create a file `<YOUR_GH_USERNAME>.json`
inside `Submissions/` folder, and then fill it up with following content.  
⚠️ Please remove the `@` from your GitHub username.  
(**Don't include the square brackets "[ ]" or angle brackets "< >" !!! They are just there to indicate an example placeholder.**)

```json
{
  "name": "[YOUR_FULL_NAME]",
  "img": "[YOUR_IMG_URL]",
  "email": "[YOUR_EMAIL_ADDRESS]",
  "links": {
    "website": "[YOUR_WEBSITE_URL]",
    "linkedin": "https://www.linkedin.com/in/<YOUR_LINKEDIN_USERNAME>",
    "github": "https://github.com/<YOUR_GH_USERNAME>"
  },
  "jobTitle": "[YOUR_TITLE]",
  "location": {
    "city": "[YOUR_CITY]",
    "state": "[YOUR_STATE_OR_PROVINCE]",
    "country": "[YOUR_COUNTRY]"
  }
}
```

Example with dummy values:
```json
{
  "name": "Marina Example",
  "img": "https://avatars.githubusercontent.com/u/57936?v=4",
  "email": "example@example.com",
  "links": {
    "website": "example.com",
    "linkedin": "https://www.linkedin.com/in/example",
    "github": "https://github.com/example"
  },
  "jobTitle": "iOS Developer",
  "location": {
    "city": "Example City",
    "state": "Example State",
    "country": "Example Country"
  }
}
```

### Please note!

- Profile pictures and/or images\* are allowed.
- If you do not want to fill some of the fields, leave them blank (e.g. `state: "",`).
- Your pull request will only be accepted if it follows the example above. It **cannot** have anything else.

Please submit a Pull Request to be added to this list. If you are unsure how to do this, please check out _Contributing To Open Source_ video in the course curriculum.

- How to add profile image to your WomenInSwift JobBoard profile using Github avatars.

1. Go to your profile on GitHub.com
2. Append to your GitHub profile url “.png”, so it will look like this:

https://github.com/example.png

3. Hit enter and the browser will generate a page with your image, it look like this:
  https://avatars.githubusercontent.com/u/57936?v=4


4. Copy url of this page and paste it in `Submissions/<YOUR_GH_USERNAME>.json` file

### Resources

All icons have been sourced from [Material Design Icons](https://materialdesignicons.com) and [Octicons](https://octicons.github.com/)
