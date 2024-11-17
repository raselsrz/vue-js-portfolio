
<template>

    <main>
        <!-- my Services design in web development -->
<section class="services">
    <h1>Services</h1>
    <p class="title" >My services in web development</p>
    <div class="services-container">
        <div class="service">
            <h2>Web Design</h2>
            <p>Designing websites that are user-friendly and visually appealing.</p>
        </div>
        <div class="service">
            <h2>Web Development</h2>
            <p>Developing websites that are fast, responsive, and interactive.</p>
        </div>
        <div class="service">
            <h2>SEO</h2>
            <p>Optimizing websites for search engines to increase visibility and traffic.</p>
        </div>
        <div class="service">
            <h2>E-Commerce Development</h2>
            <p>Building secure and scalable online stores with seamless payment integration.</p>
        </div>
        <div class="service">
            <h2>API Development</h2>
            <p>Creating robust APIs for smooth communication between systems and services.</p>
        </div>
        <div class="service">
            <h2>WordPress Development</h2>
            <p>Designing and customizing WordPress themes and plugins to meet your needs.</p>
        </div>
        <div class="service">
            <h2>Mobile App Development</h2>
            <p>Building responsive mobile applications for both Android and iOS platforms.</p>
        </div>
        <div class="service">
            <h2>Performance Optimization</h2>
            <p>Improving website speed, load times, and overall user experience.</p>
        </div>
        <div class="service">
            <h2>Database Management</h2>
            <p>Designing and optimizing databases for high performance and reliability.</p>
        </div>
        <div class="service">
            <h2>Maintenance & Support</h2>
            <p>Providing ongoing support and maintenance to ensure your website runs smoothly.</p>
        </div>
    </div>
</section>

            


    </main>



</template>

<style scoped>
    .services {
        padding: 50px 0;
        background-color: hsla(160, 100%, 37%, 1);
        border-radius: 10px;
        margin-top: 30px;
    }

    .services h1 {
        font-size: 2.6rem;
        font-weight: 500;
        position: relative;
        top: -10px;
        text-align: center;
        color: #fff;
        text-transform: uppercase;
    }

    .services .title{
        text-align: center;
        color: #fff;
        font-size: 1.2rem;
        margin-bottom: 30px;
    }

    .services-container {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
        gap: 20px;
        justify-content: center;
        align-items: center;
        padding: 0 20px;
    }

    .service {
        background-color: hsla(120, 2%, 10%, 0.2);
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        text-align: center;
    }

    .service h2 {
        font-size: 1.5rem;
        margin-bottom: 10px;
    }

    .service p {
        font-size: 1rem;
    }

    @media (min-width: 768px) {
        .services-container {
            grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
        }

        .service {
            padding: 30px;
        }

        .service h2 {
            font-size: 2rem;
        }

        .service p {
            font-size: 1.2rem;
        }
    }


</style>