<template>
    <div>
        <div class="container">
            <div class="loading"></div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {

        }
    },
};
</script>

<style scoped>
.container {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
}

.loading {
    width: 100px;
    height: 100px;
    border-radius: 100%;
    border: 5px #ffffff solid;
    border-right-color: #87ceeb;
    animation: loading 1s linear infinite;
}

@keyframes loading {
    0% {
        transform: rotate(0deg);
    }

    100% {
        transform: rotate(360deg);
    }
}
</style>
