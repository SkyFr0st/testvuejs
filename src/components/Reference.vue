<template>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/boxicons@latest/css/boxicons.min.css">
    <div class="contact">
        <h1>Contact</h1>
        <div class="social">
            <a href="https://th-th.facebook.com/" target="_blank"><i class="bx bxl-facebook"></i></a>
            <a href="https://x.com/" target="_blank"><i class="bx bxl-twitter"></i></a>
            <a href=""><i class="bx bxl-instagram"></i></a>
            <a href="https://www.youtube.com/" target="_blank"><i class="bx bxl-youtube"></i></a>
        </div>
        <div class="links">
            <p>Email : 66309010003@thonburi.ac.th</p>
            <p>Tel : 000-000-0000</p>
        </div>
        <p>&#169; Natthawat All Right Reserved.</p>
    </div>
</template>
    
<script setup lang='ts'>
    
</script>
    
<style scoped>
.contact {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.social a {
    font-size: 27px;
    margin: 0.5rem;
}

.social a .bx {
    padding: 5px;
    color: #fff;
    background: #000000;
    border-radius: 50%;
}

.social a .bx:hover {
    background: var(--main-color);
}

.links {
    margin: 1rem 0 1rem;
}

.links a {
    font-size: 1rem;
    font-weight: 500;
    color: var(--second-color);
    padding: 1rem;
}

.links a:hover {
    color: var(--main-color);
}

.contact p{
    text-align: center;
}

.contact h1{
    text-align: center;
}

.contact{
    background-color: gray;
}

</style>