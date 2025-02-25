<template>
    <div className="header">
        <div className="header_names">горящие</div>
        <div className="header_names">спринты</div>
        <div className="header_names">прочее</div>
        <div className="header_names">повестка</div>
    </div>

</template>


<script>
    export default {
        
    }

</script>


<style scoped>
.header {
    background-color: white;
    box-shadow: 0px 2px 5px 0px rgb(227, 222, 222);
    display: flex;
    padding: 13px;
}
.header_names {
    margin-right: 20px;
    margin-left: 20px;
    font-size:19px;
    font-weight: 1000;
}

</style>