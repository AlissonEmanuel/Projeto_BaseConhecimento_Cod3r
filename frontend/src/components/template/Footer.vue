<template>
    <footer class="footer">
        <span>Copyright: Developed By - <strong>Alisson Emanuel </strong> © 2021</span>
    </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style>
    .footer {
        grid-area: footer;
        background-color: #DDD;
        color: #333;
        
        display: flex;
        justify-content: flex-end;
        align-items: center;
        padding-right: 10px;
    }
</style>