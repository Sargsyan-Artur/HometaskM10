# HometaskM10

npm run postinstall \
npm run start-server \
npm run test \

# Parallel execution
npm run test -- --instances=3

# Generate Allure Reports
npm run rp


#Note installing Allure Reporter
npm install allure-commandline\
npm install mocha-allure-reporter\
protractor.conf.js / reporter = mocha-allure-reporter\
package.json / reporting: allure generate allure-results --clean -o allure-report && allure open allure-report



