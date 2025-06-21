<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css">
</head>
<title>Passowrd Generator</title>


<body>
  <div class="container d-flex justify-content-center align-items-center min-vh-100">
    <div class="d-flex flex-column">
      <h1>Passowrd Generator</h1>
      <div class="d-flex flex-column gap-2 mt-2">
        <label for="passwordLenght" class="text-uppercase fw-bold">panjang password</label>
        <input class="form-control" id="passwordLenght" type="number" />
        <label for="password" class="text-uppercase fw-bold">password</label>
        <input class="form-control" id="password" type="password"  />
        <button onclick="getPassword()" class="btn btn-dark text-uppercase fw-bold btn-lg mt-2">Generate Password</button>
        <a onclick="savePassword()" id="saveButton" class="btn btn-primary text-uppercase fw-bold btn-lg mt-2">Save Passowrd</a>
      </div>
    </div>
  </div>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/js/bootstrap.bundle.min.js"></script>
  <script src="index.js"></script>
</body>


</html>
