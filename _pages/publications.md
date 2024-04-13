---
layout: default
permalink: /publications/
---

<style>
/* Style for the publication list container */
.publication-list {
  list-style-type: none;
  padding: 0;
}

/* Style for each publication item */
.publication-item {
  margin-bottom: 20px;
  padding-bottom: 40px;
}

/* Style for publication title */
.publication-title {
  font-weight: bold;
  font-size: 1.2em;
}

/* Style for publication authors */
.publication-authors {
  /* font-style: italic; */
}

/* Style for publication details */
.publication-details {
  font-size: 0.9em;
}

/* Style for publication abstract */
.publication-abstract {
  margin-top: 5px;
}

/* Style for publication link */
.publication-link {
  color: #007bff; /* Blue color for link */
  text-decoration: none;
}

.publication-link:hover {
  text-decoration: underline;
}

.publication-thumbnail {
  float: left; /* Float the thumbnail to the left */
  margin-right: 10px; /* Add some space between the thumbnail and the publication details */
}

/* Style for the publication thumbnail image */
.publication-thumbnail img {
  max-width: 200px; /* Limit the maximum width of the thumbnail image */
  height: auto; /* Maintain aspect ratio */
  border-radius: 5px; /* Add some border radius for a rounded appearance */
}
</style>

# Publications

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Academic Publication List</title>
  <link rel="stylesheet" href="styles.css"> <!-- Assuming the CSS file is named styles.css -->
</head>
<body>

<ul class="publication-list">
  <li class="publication-item">
    <div class="publication-thumbnail">
      <img src="https://juansala.github.io/media/Images/sofi_diagram.PNG" alt="Publication 1 Thumbnail">
    </div>
    <div class="publication-details">
      <div class="publication-title">Multi-Robot Visual Control of Autonomous Soft Robotic Fish</div>
      <div class="publication-authors"><strong>Juan Salazar</strong>, Levi Cai, Braden Cook, Daniela Rus</div>
      <div class="publication-details">IEEE OES AUV Symposium, 1-6, 2022</div>
      <!-- <div class="publication-abstract">
      </div> -->
      <div class="publication-link">
        <a href="https://juansala.github.io\media\Docs\IEEE_AUV_2022_SoFi_Final.pdf" target="_blank">paper</a>
      </div>
    </div>
  </li>
  
  <li class="publication-item">
    <div class="publication-thumbnail">
      <img src="https://juansala.github.io\media\Images\grammar_example.PNG" alt="Publication 2 Thumbnail">
    </div>
    <div class="publication-details">
      <div class="publication-title">Graph Grammar-Based Automatic Design for Heterogeneous Fleets of Underwater Robots</div>
      <div class="publication-authors">Allan Zhao, Jie Xu, <strong>Juan Salazar</strong>, Wei Wang, Pingchuan Ma, Daniela Rus, and Wojciech Matusik</div>
      <div class="publication-details">International Conference on Robotics and Automation (ICRA), 3143-3149, 2022</div>
      <!-- <div class="publication-abstract"> 
      </div> -->
      <div class="publication-link">
        <a href="https://juansala.github.io\media\Docs\Graph_Grammar-Based_Automatic_Design_for_Heterogeneous_Fleets_of_Underwater_Robots_ICRA22.pdf" target="_blank">paper</a> <!-- Link to the PDF file -->
      </div>
    </div>
  </li>
</ul>

</body>