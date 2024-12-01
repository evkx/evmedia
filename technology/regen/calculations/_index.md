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
<img src="https://media.evkx.net/multimedia/technology/regen/calculations/consumption_st.png">
<p>consumption.png</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/regen/calculations/fullstop_st.jpg">
<p>fullstop.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/regen/calculations/kinetic_st.png">
<p>kinetic.png</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/regen/calculations/pikespeak_st.jpg">
<p>pikespeak.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/regen/calculations/saltfjellet_st.jpg">
<p>saltfjellet.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/regen/calculations/soc_st.jpg">
<p>soc.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/regen/calculations/stop_st.jpg">
<p>stop.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/regen/calculations/windtunnel_st.jpg">
<p>windtunnel.jpg</p>
</div>
</div>
