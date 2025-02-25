<template>
    <div className="task">
    <button>Выполнено</button>
    <div className="info">бебебе делаем то се</div>
    <div className="date">24.04.2006</div>
        
    </div>
</template>
  
  
  <script>
      export default {
          
      }
  
  </script>
  
  
  <style scoped>
  .task {
    height: 60px;
    width: 30%;
    background-color: #99f;
    position: absolute;
    right:0;
    margin-right: 80px;
    margin-top: 40px;
    display: flex;
    border-radius: 8px;
    
  }
  button {
    height: 24px;
    position: absolute;
    right:0;
    margin-right: 15px;
    bottom:0;
    margin-bottom: 18px;

    border: solid;
    border-color: blue;
    background-color: blue;
    border-radius: 5px;
    
    

  }
.info {
    align-items: center;
    margin-left: 15px;
    margin-top: 20px;
}
.date {
    align-items: center;
    margin-left: 100px;
    margin-top: 20px;
}

  
  </style>