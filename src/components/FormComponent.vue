<template>
    <section>
        <div class="container py-5">
            <h1>Scrivici!<br>Ti contatteremo al più presto.</h1>
            <div class="form">
                <div class="mb-3">
                    <input type="text" class="text" placeholder="Nome e Cognome">
                </div>
                <div class="mb-3">
                    <input type="email" class="text" placeholder="Email">
                </div>
                <div class="mb-3">
                    <input type="text" class="text" placeholder="Oggetto">
                </div>
                <div class="mb-3">
                    <textarea type="text" class="text" placeholder="Messaggio" rows="5" cols="50"></textarea>
                </div>
                <div class="check">
                    <input  type="checkbox" value="" id="flexCheckDefault">
                    <label class="form-check-label" for="flexCheckDefault"><span style="color: var(--secondary-color)">Privacy Policy.</span> Acconsento al Trattamento dei dati personali*</label>
                </div>
                <a href="#">Invia</a>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'FormComponent'
}
</script>

<style lang="scss" scoped>
h1 {
    font-size: 3rem;
    color: var(--secondary-color);
    font-weight: 700;
    text-align: center;
}

.form {
    width: 80%;
    margin: 3rem auto;

    .text {
        padding: 0.5rem 1rem;
        width: 100%;
        border-color: rgba(225,225,225,1);
        border-width: 1px;
        border-style: solid;
    }

    .check {
        margin-bottom: 1.5rem;

        input {
            margin-right: 0.5rem;
        }
    }

    a {
        font-size: 1.3rem;
        background-color: var(--secondary-color);
        padding: 0.5rem 2rem;
        color: var(--main-color);
        text-transform: uppercase;
        text-decoration: none;
        font-weight: 700;
    }
}
</style>