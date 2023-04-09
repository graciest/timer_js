# timer_js
Timer for JavaScript

<h1> HTML </h1>


<code>
<div class="ts-count-down" data-date="April 24, 2023 15:03:26"></div> 
</code>


<h1> CSS </h1>

<code>
.ts-count-down {
    display: flex;
    justify-content: space-between;
    margin-bottom: 1.25rem;
    font-size: 2.5rem;
    font-weight: 400;
    text-shadow: .375rem .3125rem 1.5625rem rgba(28, 244, 194, 0.274);
    color: yellow;
    font-weight: bold;
}

.ts-count-down div {
    display: block;
    width: 100%;
    position: relative;
}

.ts-count-down div:last-child .ts-cc-number:after {
    display: none;
}

.ts-count-down div .ts-cc-number {
    position: relative;
    width: 100%;
    display: block;
}

.ts-count-down div .ts-cc-number:after {
    bottom: 0;
    content: "\f111";
    font-weight: 900;
    font-family: 'Inter', sans-serif;
    position: absolute;
    height: .625rem;
    margin: auto;
    font-size: .625rem;
    top: 0;
    opacity: .2;
    right: -0.625rem;
    -webkit-font-smoothing: antialiased;
}

.ts-count-down .ts-cc-description {
    display: block;
    font-size: .875rem;
    /* opacity: .5; */
}
</code>
</pre>

<h1> Preview </h1>

<img src="https://i.ibb.co/Ntg3cPD/image.png" alt="Preview" >
