<template>

    <main>
        
        <!-- contact page design -->
        <div class="contact">
            <h1>Contact Page</h1>
            <p>Feel free to contact us</p>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </div>


    </main>




</template>

<style scoped>
    /* contact page css */
    .contact {
        padding: 100px 0;
        text-align: center;
    }

    .contact h1 {
        font-size: 36px;
        font-weight: 700;
        margin-bottom: 30px;
        text-transform: uppercase;
        color: hsla(160, 100%, 37%, 1);
    }

    .contact p {
        font-size: 16px;
        color: #fff;
        margin-bottom: 20px;
    }

    .contact form {
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .contact form label {
        font-size: 16px;
        color: #fff;
        margin-bottom: 10px;
    }

    .contact form input,
    .contact form textarea {
        padding: 10px;
        margin-bottom: 20px;
        width: 100%;
        border-radius: 5px;
        border: none;
    }

    .contact form button {
        padding: 10px 30px;
        border-radius: 5px;
        background-color: hsla(160, 100%, 37%, 1);
        color: #fff;
        font-weight: 500;
        border: none;
        cursor: pointer;
    }

    .contact form button:hover {
        background-color: hsla(160, 100%, 37%, 1);
    }

</style>