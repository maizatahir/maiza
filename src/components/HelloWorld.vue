
<template>
  <div class="greetings">
       <ul>
          <h2>Hello World Maiza</h2>
          <ul>
            <li class="assignment-header">
              <span>Assignment List</span>
              <span>Month</span>
            </li>
            <ul>
              <li>Git</li>
              <li>Agile/Scrum</li>
            </ul>
          </ul></ul>
          
        </div>
      </template>
      
<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}
.assignment-header {
  display: flex;
  justify-content: space-between; 
  width:200px;
  
}


@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
