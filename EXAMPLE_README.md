[PROJECT_NAME]
========
[STATUS BADGES]

#### [LANGUAGE SDK/WRAPPER/LIBRARY NAME] for Tomorrow.io API ####

The aim of the project is to [DESCRIPTION] for [Tomorrow.io API](https://app.tomorrow.io/). 

### What's Included ###
- [ ] [GET Timeline](https://docs.tomorrow.io/v4/reference/get-timelines)
- [ ] [POST Timelines](https://docs.tomorrow.io/v4/reference/post-timelines)

### Usage ###
[USAGE EXAMPLE BELOW]
This code imports the SDK and initializes it with your personal api key. It then makes a request to Tomorrow.io's endpoints with url parameters, waits for response and handles returned timesteps.

```javascript
import tomorrow from 'MODULE_NAME';
tomorrow.realtime({fields: ["precipitation"], lat: 22, lon: 22]}).then((response)=> {
    // DO WHATEVER YOU WANT HERE
})
```

### Contributing ###
[PROJECT_NAME] is a community project. We invite your participation through issues and pull requests! Please read through our [contributing guidelines](https://github.com/YOUR_USER/THIS_REPO/blob/master/CONTRIBUTING.md), where you will find directions for opening issues, coding standards, and notes on development.

When adding or changing a service please add tests.

### Development ###
1. Install [...]
1. Clone this repository.
1. Run [...]

This project has quite a backlog of suggestions! If you're new to the project, maybe you'd like to open a pull request to address one of them: https://github.com/[YOUR_USER]/[THIS_REPO]/issues

### Change log ###
[Releases](https://github.com/[YOUR_USER]/[THIS_REPO]/releases)

### Related Projects ###
- [Related Project 1]()
- [Related Project 2]()
- ...

### Contributors ###
This project exists thanks to all the people who contribute [[Contribute](https://github.com/YOUR_USER/THIS_REPO/blob/master/CONTRIBUTING.md)] 

### License ###
Licensed under the [LICENSE_TYPE] license.
