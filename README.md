# Lost-in-dark
var express = require('express');
var path = require ('path');
var router = express.Router();

/* GET home page. */
router.get('/', function(req, res, next) {
    // make these parenthesis reach the html file in the views folder //
  res.sendFile(path.join(_First project, '/own.html');
});

module.exports = router;
