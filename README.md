## Ex.10 Responsive Web Design using Bootstrap
## Date:10-05-2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.

## DESIGN STEPS:
### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pharmaceuticals</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet">
    <style>
        .navbar {
            background-color: rgba(0, 0, 0, 0.7); 
        }

        .card {
            margin: 20px; 
        }
    </style>
</head>
<body>

<nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">AYURVEDIC PHARMANCY</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
                <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    <i class="fas fa-info-circle"></i> About
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
                    <a class="dropdown-item" href="#">Ayurvedic Herbs History</a>
                    <a class="dropdown-item" href="#">Ayurvedic Herbs</a>
                    <a class="dropdown-item" href="#">Herbal Medicine</a>
                </div>
            </li>
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownProducts" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    <i class="fas fa-pills"></i> Products
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdownProducts">
                    <a class="dropdown-item" href="#">Medications</a>
                    <a class="dropdown-item" href="#">Supplements</a>
                    <a class="dropdown-item" href="#">Medical Devices</a>
                </div>
            </li>
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownContact" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    <i class="fas fa-phone-alt"></i> Contact
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdownContact">
                    <a class="dropdown-item" href="#">Customer Support</a>
                    <a class="dropdown-item" href="#">Sales</a>
                    <a class="dropdown-item" href="#">Feedback</a>
                </div>
            </li>
        </ul>
        <ul class="navbar-nav ml-auto">
            <li class="nav-item">
                <a class="nav-link" href="#">Login</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Register</a>
            </li>
        </ul>
    </div>
</nav>

    <div style="display:flex;">
        <div class="card" style="width: 20rem; margin:20px">
            <img src="ayu.png" class="card-img-top" alt="..." style="height: 300px;">
            <div class="card-body">
              <h5 class="card-title">Ayurvedic Herbs History</h5>
              <p class="card-text">They composed all the information about the herbs and medicines in form of Shlokas or hymns. It is believed that all the compilations related to healing and medicines were contained in the four Vedas – Rig Veda, Yajur Veda, Sama Veda and the Atharva Veda. It was around 1500 to 1000 BC when Ayurveda in India developed.</p>
              <a href="#" class="btn btn-primary">Read More</a>
            </div>
        </div>


          <div class="card" style="width: 20rem; margin:20px">
            <img src="her.png" class="card-img-top" alt="..." style="height: 300px;">
            <div class="card-body">
              <h5 class="card-title">Ayurvedic Herbs</h5>
              <p class="card-text">Ayurvedic herbs and spices play an important part in a holistic approach to health and wellness. Ayurveda is a traditional medicine system from India that focuses on promoting wellness of body, mind, and spirit. The holistic approach combines lifestyle changes, diet, and exercise</p>
              <a href="#" class="btn btn-primary">Read More</a>
            </div>
          </div>


          <div class="card" style="width: 20rem; margin:20px">
            <img src="med.png" class="card-img-top" alt="..." style="height: 300px;">
            <div class="card-body">
              <h5 class="card-title">Herbal Medicine</h5>
              <p class="card-text">Herbal medicine is used to treat many conditions, such as allergies, asthma, eczema, premenstrual syndrome, rheumatoid arthritis, fibromyalgia, migraine, menopausal symptoms, chronic fatigue, irritable bowel syndrome, and cancer, among others.</p>
              <a href="#" class="btn btn-primary">Read More</a>
            </div>
          </div>
    </div>


<footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 PharmaCompany. All rights reserved.</p>
</footer>


<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
## OUTPUT:
![alt text](<vijay/Screenshot (11).png>)
## RESULT:
The program for responsive web design using Bootstrap is completed successfully.
