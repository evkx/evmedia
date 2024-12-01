<style>
    .image-gallery {
        display: flex;
        flex-wrap: wrap;
        gap: 10px;
        justify-content: center;
        padding: 10px;
    }
    .image-gallery img {
        width: 150px;
        height: auto;
        border: 1px solid #ddd;
        border-radius: 5px;
    }
    .image-gallery div {
        flex: 1 1 calc(33.333% - 20px); /* Three images per row on large screens */
        max-width: 150px;
        text-align: center;
    }
    @media (max-width: 768px) {
        .image-gallery div {
            flex: 1 1 calc(50% - 20px); /* Two images per row on medium screens */
        }
    }
    @media (max-width: 480px) {
        .image-gallery div {
            flex: 1 1 100%; /* One image per row on small screens */
        }
    }
</style>
<h1 style ="text-align: center;"> Image Overview </h1> <div class="image-gallery">
<div>
<img src="https://media.evkx.net/multimedia/technology/lights/rearlights/audia6rearlights_1_st.jpg">
<p>audia6rearlights_1.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/lights/rearlights/audiq6rearlightsconstruction_st.jpg">
<p>audiq6rearlightsconstruction.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/lights/rearlights/audiq8etronrearlight_st.jpg">
<p>audiq8etronrearlight.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/lights/rearlights/audiq8rearlightsignatures_st.jpg">
<p>audiq8rearlightsignatures.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/lights/rearlights/audiq8rearlights_1_st.jpg">
<p>audiq8rearlights_1.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/lights/rearlights/audiq8rearlights_2_st.jpg">
<p>audiq8rearlights_2.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/lights/rearlights/audiq8rearlights_3_st.jpg">
<p>audiq8rearlights_3.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/lights/rearlights/audiq8rearlights_4_st.jpg">
<p>audiq8rearlights_4.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/lights/rearlights/eqsrearlights_st.jpg">
<p>eqsrearlights.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/lights/rearlights/hiphixrearlights_st.jpg">
<p>hiphixrearlights.jpg</p>
</div>
</div>
