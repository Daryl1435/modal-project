<template>
    <div class="backdrop">
        <div class="modal">
            <p>modal content</p>
        </div>
    </div>
</template>

<style >
    .modal{
        width: 400px;
        padding: 20px;
        margin: 200px auto;
        background: white;
        border-radius: 10px;
    }
    .backdrop{
        top: 0;
        position: fixed;
        background: lightgray;
        width: 100%;
        height: 100%;
    }
</style>