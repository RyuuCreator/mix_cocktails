<template>
    <footer>
        <span>
            Technologies utilisées: NodeJs, Vue3 js, MongoDB. Plus d'informations
            sur GitHub
            <a href="https://github.com/vincentauzias/MIX_Cocktails"
                ><i class="fab fa-github"></i
            ></a>
        </span>
        <hr class="footer-hr" />
        <span
            >Contributeurs: Vincent Auzias - Mickael Tailhades - Emmanuelle
            Dufrenay</span
        >
    </footer>
</template>

<script>
export default {
    name: "Footers",
};
</script>

<style scoped>
footer {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: #82a7ca;
    width: 100%;
    height: 8vh;
}

.footer-hr {
    border: none;
    background-color: #333;
    width: 50%;
    height: 1px;
}

.fa-github {
    font-size: 1.25em;
    color: #333;
}

@media (max-width: 900px) {
    footer {
        font-size: 12px;
    }
}
@media screen and (max-width: 450px) and (orientation: portrait) {
    footer {
        height: 100px;
        text-align: center;
    }
}
</style>
