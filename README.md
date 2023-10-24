# QAChallenge

## Steps to run cypress tests

- npx cypress run --headed //Executes all the tests inside e2e folder

- npx mochawesome-merge cypress/screenshots/\*.json -o cypress/screenshots/output.json // command to aggregate mochawesome reports

- npx marge cypress/screenshots/output.json --reportDir ./ --inline // command to generate final html reports

## Test set up

- e2e folder consists of two spec files.One spec file represents UI tests, and second spec file represents API tests

- Language used - Typecript

- Reporting tool - mocha awesome

## API tests

- API tests validates waether API that returns weather data for a set of coordinates stored in fixtures folder

## UI tests

- UI tests validates that application can use the current location and show the weather card, add/delete a location , show weather details on clicking of a weather card, also mocked data for one of the location to check if there UI displays the data correctly as supplied by mock data
