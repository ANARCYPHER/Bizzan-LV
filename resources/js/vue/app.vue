<template>
    <div class="todoListContainer">
        <div class="heading">
            <h2 id="title">Todo list</h2>
            <add-item-form />
        </div>
        <list-view />
    </div>
</template>

<script>
import addItemForm from "./addItemForm"  
import ListView from "./ListView" 

export default {
    components: {
       addItemForm,
       listView
    }
}
</script>

<style scoped>
.todoListContainer {
    width: 350px;
    margin: auto;
}

.heading {
    background: #6e6e6e;
    padding: 10px;
}

#title {
    text-align: center;
}
</style>
