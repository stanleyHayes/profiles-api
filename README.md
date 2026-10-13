# profiles-api

profiles api is an application containing JavaScript. The checked-in dependency manifests use Express, MongoDB via Mongoose. Source modules cover `applicants`, `certifications`, `comments`, `companies`, `education`, `employment`, `favorites`, `jobs`, `likes`, `posts`.

## Repository layout

- `controllers/` — 15 tracked file(s); source examples: `controllers/applicants.js`, `controllers/certifications.js`.
- `middleware/` — 1 tracked file(s); source examples: `middleware/auth.js`.
- `models/` — 15 tracked file(s); source examples: `models/applicant.js`, `models/certification.js`.
- `routes/` — 15 tracked file(s); source examples: `routes/applicants.js`, `routes/certifications.js`.

## Local setup

Run each package setup block from the repository root. For workspace repositories, install dependencies at the root before running application-specific scripts.

Clone this repository and enter its directory:

```sh
git clone https://github.com/stanleyHayes/profiles-api.git
cd profiles-api
```

### Node package: `package.json`

Use Node.js and npm.

```sh
npm install
```

- `node index.js` — executes the package entry point.
- The package test script is a placeholder and exits with an error; it does not run an automated test suite.

## Source entry points

- [controllers/applicants.js](controllers/applicants.js)
- [controllers/certifications.js](controllers/certifications.js)
- [controllers/comments.js](controllers/comments.js)
- [controllers/companies.js](controllers/companies.js)
- [controllers/education.js](controllers/education.js)
- [controllers/employment.js](controllers/employment.js)
- [controllers/favorites.js](controllers/favorites.js)
- [controllers/jobs.js](controllers/jobs.js)

## Development notes

Commands above come from the tracked manifests and source layout. External services and runtime configuration may be required. Documentation updates do not establish that the application is deployed or that its tests pass.
