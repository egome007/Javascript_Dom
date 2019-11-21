<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>UFO Finder</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootswatch/3.3.7/superhero/bootstrap.min.css">
  <link href="https://fonts.googleapis.com/css?family=Ubuntu" rel="stylesheet">
  <link rel="stylesheet" href="static/css/style.css">
</head>

<body>
  <div class="wrapper">
    <nav class="navbar navbar-default">
      <div class="container-fluid">
        <div class="navbar-header">
          <a class="navbar-brand" href="index.html">UFO Sightings
            <img class="nav-ufo" src="static/images/ufo.svg">
          </a>
        </div>
      </div>
    </nav>
    <div class="hero text-center">
      <h1>UFO Sightings</h1>
      <p>The Truth is Out There</p>
    </div>
    <div class="container">
      <div class="row margin-top-50">
        <div class="col-md-12">
          <aside class="filters">
            <div class="panel panel-default">
              <div class="panel-heading">Search for a specific date:</div>
              <div class="panel-body">
                <form>
                  <div class="form-group">
                    <ul class="list-group" id="filters">
                      <li class="filter list-group-item">
                          <label for="date">Enter a Date</label>
                          <input class="search_box" id="datetime" type="text" placeholder="1/11/2011">
                          <button id="fake" onclick="return false;" >Submit</button>
                          
                      </li>
                    </ul>
                  </div>
                  <button id="filter-btn" type="submit" class="btn btn-default" onkeyup="clickSelect()">Reset Table</button>
                </form>
              </div>
            </div>
          </aside>
        </div>
        <div class="col-md-12">
          <div id="table-area" class="table-responsive">
            <table id="ufo-table" class="table table-striped">
              <thead>
                <tr>
                  <th class="table-head">Date</th>
                  <th class="table-head">City</th>
                  <th class="table-head">State</th>
                  <th class="table-head">Country</th>
                  <th class="table-head">Shape</th>
                  <th class="table-head">Duration</th>
                  <th class="table-head">Comments</th>
                </tr>
              </thead>
              <tbody>            
              </tbody>
            </table>
          </div>
        </div>
      </div>
    </div>
    <footer class="footer">
      <span class="bottom">UFO Sightings</span>
    </footer>
  </div>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/d3/4.11.0/d3.js"></script>
  <script src="static/js/data.js"></script>
  <script src="static/js/app.js"></script>
</body>

</html>
# Javascript_Dom
