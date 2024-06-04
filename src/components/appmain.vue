<script>
export default {
    data() {
        return {

        };
    },

    methods: {

    },
}
</script>

<template>
    <div class="articles">
        <h3>Articles and tips</h3>
        <h5>Latest From The Blog</h5>
        <div class="images">
            <div class="blog1">
                <div class="card1">
                    <img src="../assets/images/artist-blog-03-480x356.jpeg" alt="" srcset="">
                    <div class="description">
                        <p>Artist</p>
                        <p>Lorem ipsum dolor sit amet consectetur.</p>
                    </div>

                </div>
            </div>
            <div class="blog2">
                <div class="card2">
                    <p>Artist</p>
                    <p>Lorem ipsum dolor sit amet.</p>
                </div>
            </div>
            <div class="blog3">
                <div class="card3">
                    <img src="../assets/images/artist-blog-01-480x356.jpg" alt="" srcset="">
                    <div class="description">
                        <p>Artist</p>
                        <p>Lorem ipsum dolor sit amet consectetur.</p>
                    </div>

                </div>
            </div>
        </div>
        <div class="details">
            <p style="color: black;">Get into details now ?</p>
            <p style="color: #ef6f31;">View all posts <i class="fa-solid fa-arrow-right"></i></p>
        </div>
    </div>

</template>

<style scoped>
p {
    margin: 0;
}

h3 {
    text-align: center;
    margin-bottom: 0.5rem;
    color: #6ac5f1;
}

h5 {
    text-align: center;
    margin-bottom: 0.5rem;
    color: black;
}

.images {
    display: flex;
    justify-content: space-between;
    padding: 0 5rem;
}

.details {
    display: flex;
    justify-content: center;
    margin-top: 1rem;
}

.articles {
    background-color: #F5F5F5;
}

.blog1,
.blog3 {
    width: 100px;
    height: 150px;
    background-color: white;
}

.card1,
.card3 {
    width: 100%;
}

.description {
    width: 100%;
    font-size: 0.7rem;
    color: black;
    padding: 2px 2px 2px 6px;
    text-align: start;
}

.card1 img {
    width: 100%;
    object-fit: cover;
}

.card3 img {
    width: 100%;
    object-fit: cover;
}

.blog2 {
    background-image: url(../assets/images/artist-blog-02-500x680.jpg);
    width: 200px;
    height: 300px;
    background-size: cover;
    display: flex;
    align-items: end;
}
</style>