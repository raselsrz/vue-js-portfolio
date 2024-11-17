<script>
import { defineComponent } from 'vue';
import aboutMe from '../assets/me.png';
import Cv from '../assets/cv.pdf';

export default defineComponent({
  name: 'AboutMe',
  data() {
    return {
      aboutMe,
      Cv,
    };
  },
});
</script>



<template>


    <main>

        <!-- about me desgin -->
        <section class="about-me" id="about-me">
            <div class="container">
                <div class="section-title">
                    <h2>About Me</h2>
                </div>
                <div class="row">
                    <div class="col-lg-4">
                        <div class="about-me-img">
                            <img :src="aboutMe" alt="about me" />
                        </div>
                    </div>
                    <div class="col-lg-8">
                        <div class="about-me-text">
                            <p>
                                Hi, I’m Md Rasel Islam, a passionate Full Stack Developer with over 4 years of experience crafting innovative and scalable web solutions. I specialize in Laravel, PHP, JavaScript, and WordPress, and I’ve had the opportunity to work on projects across different industries and countries.
                            </p>
                            <p>
                                My journey in tech started with a desire to build something meaningful, and that’s exactly what I do—designing, developing, and deploying applications that solve real-world problems. Whether it’s backend development, API integrations, or front-end user interfaces, I’m committed to delivering high-quality, user-friendly experiences.


                            </p>
                            <p>
                                I thrive in collaborative environments, working closely with clients to understand their needs and transform their ideas into reality. I believe in continuous learning and always stay up to date with the latest trends and technologies in web development.

                            </p>
                            <p>
                                Outside of coding, I’m a problem solver at heart, and I enjoy exploring new tools and techniques to make development more efficient and enjoyable. Let's work together and bring your next idea to life!


                            </p>
                            <a class="btn" :href="Cv" download>
      Download CV
    </a>
                        </div>

                    </div>
                </div>
            </div>
        </section>
        <!-- end about me desgin -->
    </main>



</template>

<style scoped>
    /* about me css */
    .about-me {
        padding: 100px 0;
    }

    .about-me .section-title h2 {
        font-size: 36px;
        font-weight: 700;
        margin-bottom: 30px;
        text-transform: uppercase;
        text-align: center;
        color: hsla(160, 100%, 37%, 1);
    }

    .about-me .row {
        align-items: center;
    }

    .about-me-img img {
        border-radius: 10px;
    }

    .about-me-text p {
        font-size: 16px;
        color: #fff;
        margin-bottom: 20px;
    }

    .about-me-text a {
        display: inline-block;
        padding: 10px 30px;
        border-radius: 5px;
        background-color:  hsla(160, 100%, 37%, 1);
        color: #fff;
        font-weight: 500;
        margin-top: 20px;
    }

    .about-me-text a:hover {
        background-color:  hsla(160, 100%, 37%, 1);
    }

    .about-me .about-me-img {
        margin-bottom: 30px;
        text-align: center;
    }

    .about-me .about-me-img img{
        max-width: 100%;
        width: 350px;
        height: 350px;
        border-radius: 50%;
        object-fit: cover;
        border: 10px solid  hsla(160, 100%, 37%, 1);
        }

    /* end about me css */
</style>