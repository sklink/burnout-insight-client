# Burnout Insight

### Pitch

Get insight into the drivers of burnout before they happen. By tracking various data points of your life, we'll 
look for patterns that indicate you're heading toward burnout so that you can make positive change to avoid it.

### Details

Most important to a user's success is their consistent data entry. This needs to 
happen:

 - when users remember the data they want to enter
   - i.e. mood may change throughout the day
 - on a daily basis
 - with the most data points we're able to gather

In order to enable their success, we'll provide multiple input interfaces:

 - React Web for Desktop and Mobile Browser
 - React Native Mobile App
 - Chrome Extension

### Deliverables

[] Setup a cross-platform baseline that supports React Native and React Web using shared logic
[] Collect user input using React Native interfaces
[] Build out an automated deployment pipeline for React Native

### Nice to Have

[] Collect data using React Web interfaces
[] Build out an automated deployment pipeline for React Web
[] Research data analysis types to determine the correct approach for this data set
[] Perform data analysis to draw conclusions about data points
[] Create a Chrome Extension


## Features

-  [Authentication and User Management](./docs/_boilerplate/UserSystem.md)

## Starting a new project

It's recommended to work from a fresh repository rather than retaining the git history.

Clone the repository and reinitialize:
```
git clone git@github.com:sklink/boilerplate-client.git project_name
cd project_name
rm -rf .git
git init
```

## Keeping your project up-to-date

Use the doc in your project at `/docs/_boilerplate/CHANGELOG.md` to determine your boilerplate version.

Compare that version to the [latest one](https://github.com/sklink/boilerplate-client/docs/_boilerplate).

Decide which changes you want to copy over and manually copy the files listed. Before doing so, be sure that
the existing file hasn't diverged from the boilerplate. Checking the file's git history is the safest way to do so:

```
git log -p path/to/filename.jsrm -rf ./git

```

*While manual copying isn't ideal, there are a number of benefits:*
 
 - *forces manual review and approval of updates going into production applications;*
 - *core files can be changed without concern about maintaining compatibility with the boilerplate; and,*
 - *boilerplate changes can be planned and refined before being added to the main repo without blocking an
 existing project's needs.*  
