# Get-Date-After-x-Days

//index.js

const addDays = require("date-fns/addDays");
const result = addDays(new Date(2021, 0, 11), 10);

module.exports = addDays;
console.log(result);
