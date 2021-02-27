# StoryBooks

> Create public and private stories from your life

This app uses Node.js/Express/MongoDB with Google OAuth for authentication

## Requirements

1. Install Node.js (backend language for application develoment)
2. Install Docker (utility CLI for containerization)
3. Install Terraform (infrastructure management)
4. Install gcloud (utility CLI for Google Cloud hosting)
4. Install GNU Make (utility CLI tool)



## Install

Add your mongoDB URI and Google OAuth credentials to the config.env file

```bash
# Install dependencies
npm install

# fix vulnerability issues
npm audit fix

# Run in development
npm run dev

# Run in production
npm start
```

## Credit

Thank to Brad Traversy for sharing its awesome [storybook](https://github.com/bradtraversy/storybooks) project 👏
