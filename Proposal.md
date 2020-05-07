#### Amber Doe Jr.

#### ActorAid

##### Description
ActorAid is a time management mobile app that coordinates a user’s schedule to maximize casting audition opportunities.

##### Use Case
Users are primarily actors who are struggling with time management. The difficulty of managing shifts at their main-income jobs and time slots for auditions has led to increased stress which affects their capabilities, leading to missed opportunities.

The product will systemize calendars across platforms and apps for viewing regular work hours, a two-click feature for manually adding irregular work hours, creating reminders, and adding alerts for local events such as workshops or new auditions. Time slot conflicts between work hours and events will be alerted to the user so that the conflict can be resolved.

The product will offer line delivery prompts for practice sessions that users can record and save to compare at a later time. The product will store practice times in a chart so that users can see their progress and manage their practice time as they see fit.

The product will prompt the user to input a stress rating twice daily and store their inputs into a chart for users to view their stress levels over time, so that they may better manage it.

The product will offer daily meditation prompts, ranging from 2 to 20 minutes, urging the user to consider their self-care and manage their stress levels. The product will store meditation times in a chart for users to view.

The product will allow users to mitigate their stress by giving them a tool that helps manage their time use and alerts them to the opportunities they are interested in pursuing.

##### Minimum Viable Product
 * User registration (database storage)
 * User login/sign-out (with database authentication)
 * Calendar with month and day views (one-click switch)
 * Capability to add regular work hours to calendar (repeated event)
 * Capability to add irregular work shifts to calendar (one time events)
 * Capability to search for local events (default search: any event containing ‘audition’ in their title or description)
 * Capability to add events to the calendar

##### Tools for MVP
 * VisualStudio Code
 * React Native SDK
 * Nuclide Atom Addition
 * RealM Database
 * Eventbrite Platform API
 * ESLint, AirBnB settings
 * Jest Testing Framework

##### Additional Features
 * Time slot conflict alert (when an event conflicts with another event or a work hour)
 * Time slot conflict resolution modal (prompt to remove event or ‘snooze’ until work hour can be taken off)
 * Reminders for calendar events (any non-work hour items on the calendar)
 * Option for reminders for all calendar events (including work hour items)
 * Capability to search for local events, with customized search, to add to calendar (user is able to search for what they are looking for such as workshops, auditions, networking events, etc)
 * Daily (optional) prompts for line delivery practice.
 * Capability to snooze daily practice prompts.
 * Daily (optional) meditation prompts.
 * Capability to snooze daily meditation prompts.
 * Capability to set specific times for practice and meditation prompts.
 * Daily (non-optional) prompts for stress level reporting.
 * Add condition that stress prompts must be at least 8 hours apart, and do not accumulate, and depends on when user signs in.
 * Create a chart of recorded stress prompt answers for the user to view.
 * Create a chart for completed practice prompts in a day for the user to view.
 * Create a chart for completed meditation prompts for the user to view.
 * Allow user to access practice prompts besides the daily prompt
 * Modify practice chart to count the number of completed practice prompts
 * Capability to record and listen to the audio of practice for the user to save in their profile
 * Capability for the user to rate their practice audios
 * Create a chart of user ratings of practice audio for the user to view.
 * User registration (database storage, Facebook credentials, Google credentials)
 * User authentication (database, Facebook, Google)

##### Tools for Additional Features
 * Calendar syncing (Google API?)
 * React Native Timer Module
 * MeetUp API
 * Backstage.com Casting RSS Feed
 * ProductionHub.com Casting Notices Alerts
 * React Native Audio Player Recorder Package
 * React Chartkick
 * Facebook Authentication
 * Google Authentication

##### Additional Information

I have a lot of ideas that I really want to work on, but I’d be very happy to have a functional in-app calendar without syncing capabilities (like to Google Calendars). I don’t feel overwhelmed by most of my ideas, but I worry that a few of them might be beyond my skill level. Do you have any resources for React Native audio management? Thanks!
