# Events Platform (frontend)

A React frontend for an event management API. Users sign up or sign in, browse events, view details, create events and join them, and see the events they have joined.

**Stack:** React 18 (Create React App), React Router, React Bootstrap, styled-components, Context API for event state, Axios.

## Structure

- `src/components`: event list, card, details, create/join forms, auth forms
- `src/context/EventContext.js`: shared event state
- `src/services`: API and auth clients

## Run

```bash
cp env.example .env   # set the API base URL
npm install
npm start
```
