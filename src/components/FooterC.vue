<template>
    <div class="footer">
        <div class="footer__wrapper d-flex">
            <h1 class="footer__heading">Баранов Антон Андреевич 211-321</h1>
            <a href="https://gitlab.com/B4R4N0VS/3sem_webexam" class="ml-12 warning border-bottom ">GIT</a>
        </div>
    </div>
    
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

    .footer__wrapper {
        max-width: 1400px;
        margin: 0 auto;
        justify-content: center;
    }

    .footer__heading {
        text-align: center;
        margin-bottom: 28px;
    }

    .footer {
        margin-top: 28px;
    }

    @media print {
        .footer {
            display: none;
        }
    }

    a {
        font-size: 32px;
    }
</style>