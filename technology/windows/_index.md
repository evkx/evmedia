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
<img src="https://media.evkx.net/multimedia/technology/windows/privacyglass_1_st.jpg">
<p>privacyglass_1.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/windows/privacyglass_2_st.jpg">
<p>privacyglass_2.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/windows/rearwindows_1_st.jpg">
<p>rearwindows_1.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/windows/rearwindows_2_st.jpg">
<p>rearwindows_2.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/windows/sidewindows_1_st.jpg">
<p>sidewindows_1.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/windows/windshield_1_st.jpeg">
<p>windshield_1.jpeg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/windows/wipers_1_st.jpg">
<p>wipers_1.jpg</p>
</div>
</div>
