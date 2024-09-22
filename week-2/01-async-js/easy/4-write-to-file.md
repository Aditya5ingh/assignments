var fs = require("fs");

fs.writeFile("a.txt", "I am Aditya", (err) => {
  console.log("saved");
});
