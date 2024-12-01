## technology\userinterface\buttons
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
    }
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
<img src="https://media.evkx.net/multimedia/technology/userinterface/buttons/audietronbuttonsinstrument_st.jpg">
<p>audietronbuttonsinstrument.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/userinterface/buttons/bmwixcenterconsolbuttons_st.jpg">
<p>bmwixcenterconsolbuttons.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/userinterface/buttons/eqssuvdoorbuttons_st.jpg">
<p>eqssuvdoorbuttons.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/userinterface/buttons/etrongtcenterconsolbuttons_st.jpg">
<p>etrongtcenterconsolbuttons.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/userinterface/buttons/kiaev6centerconsolbuttons_st.jpg">
<p>kiaev6centerconsolbuttons.jpg</p>
</div>
<div>
<img src="https://media.evkx.net/multimedia/technology/userinterface/buttons/teslamodelybuttons_st.jpg">
<p>teslamodelybuttons.jpg</p>
</div>
</div>
