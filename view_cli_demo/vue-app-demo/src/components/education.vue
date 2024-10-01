<template>
    <div id="education">
      <h2>Education</h2>
      <ul>
        <li>
          <h3>Tertiary</h3>
          <p>Bachelor of Science in Information Technology</p>
          <p>Major in Web Development</p>
          <p>Angeles City, Pampanga</p>
          <p>S.Y. 2021 - Present</p>
        </li>
        <li>
          <h3>Secondary</h3>
          <p><strong>Senior High School:</strong> Eastern Porac National High School</p>
          <p>Porac, Pampanga</p>
          <p>S.Y. 2019 - 2021</p>
          <p><strong>Junior High School:</strong> Eastern Porac National High School</p>
          <p>Porac, Pampanga</p>
          <p>S.Y. 2015 - 2019</p>
        </li>
        <li>
          <h3>Primary</h3>
          <p>Padre Burgos Elementary School</p>
          <p>Altura St., Sta. Mesa, Manila</p>
          <p>S.Y. 2009 - 2015</p>
        </li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: "Education"
  }
  </script>
  
  <style scoped>
  #education {
    background-color: #e6f7ff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    max-width: 600px;
    margin: 0 auto; 
  }
  
  h2 {
    text-align: center;
    margin-bottom: 20px;
  }
  
  ul {
    list-style-type: none;
    padding: 0;
  }
  
  li {
    margin-bottom: 20px; 
    padding-bottom: 10px;
    border-bottom: 1px solid #ccc;
  }
  
  li:last-child {
    border-bottom: none; 
  }
  
  h3 {
    margin-bottom: 10px;
    color: #2c3e50;
  }
  
  p {
    margin: 5px 0;
  }
  </style>
  