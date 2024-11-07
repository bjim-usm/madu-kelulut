---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<style>
.store-list-div::before {
    content: '';
    position: absolute;
    top: 0;
    left: 50%;
    width: 100vw;
    height: 100%;
    margin-left: -50vw;
    background-image: radial-gradient(circle, rgba(255, 255, 255, 0.7), rgba(255, 255, 255, 0.15)), url('{{ '/assets/background1.JPG' | relative_url }}');
    background-size: cover;
    background-position: center;
    z-index: -1;
}
</style>
<div>
    <div class="main-title">
        <lottie-player src="{{ "/assets/lottie.json" | relative_url }}" background="transparent" speed="1"  direction="1" mode="normal" autoplay style=" width: 100%"></lottie-player>
        <h1 >PROUDLY MADE FROM SARAWAK</h1>
        <div class="logo-list">
            <img src="{{"/assets/images/halal-logo.png" | relative_url}}"/>
            <img src="{{"/assets/images/produk-muslim.png" | relative_url}}" >
        </div>
    </div>
    <div class="store-list-div">
        <div class="content-wrapper">
            <h1>Discover the natural sweetness of Stingless Bee Honey</h1>
            <div class="store-description">
                <p>Stinglee Bee Honey is a premium honey product made from stingless bees in Sarawak. Our honey is harvested from the hives of stingless bees, which are smaller than regular honey bees. The honey is produced in nests built by the bees in various locations, such as underground or in tree crevices</p>
            </div >
        </div>
    </div>
    <div class="innovate-div">
        <div class="header">
            <h1> Why use Stingless Bee Honey? </h1>
        </div>
        <div class="innovate-row">
            <div class="innovate-col">
                <div class="compare-list">
                    <img src="{{"/assets/nutrisi1.jpg" | relative_url}}" >
                    <img src="{{"/assets/nutrisi2.jpg" | relative_url}}"  >
                </div>   
                <div class="description">
                    <h2>Rich Nutritional Profile</h2>
                    <p>It typically contains higher levels of antioxidants, vitamins, and minerals compared to conventional honey due to the diverse range of flowers the bees visit.</p>
                </div>
            </div>
            <div class="innovate-col">
                <div class="compare-list">
                    <img src="{{"/assets/flavor1.jpg" | relative_url}}"   >
                    <img src="{{"/assets/flavor2.jpg" | relative_url}}" >
                </div>   
                <div class="description">
                    <h2>Unique Flavor and Aroma:</h2>
                    <p>The honey has a distinct, often tangy flavor and aromatic profile, which varies depending on the local flora.</p>
                </div>
            </div>
        </div>
        <div class="innovate-row">
            <div class="innovate-col">
                <div class="compare-list">
                    <img src="{{"/assets/medical1.jpg" | relative_url}}"  >
                    <img src="{{"/assets/medical2.jpg" | relative_url}}">
                </div>   
                <div class="description">
                    <h2>Medicinal Properties</h2>
                    <p>It's traditionally valued for its potential anti-inflammatory, antimicrobial, and wound-healing properties. Some studies suggest it might offer benefits for gastrointestinal health and skin conditions.
                    </p>
                </div>
            </div>
            <div class="innovate-col">
                <div class="compare-list">
                    <img src="{{"/assets/sustainprod1.jpg" | relative_url}}"    >
                    <img src="{{"/assets/sustainprod2.jpg" | relative_url}}"  >
                </div>   
                <div class="description">
                    <h2>Sustainable Production</h2>
                    <p>Stingless bees play a crucial role in pollination, supporting local ecosystems. Their honey production tends to have a lower environmental impact compared to large-scale honeybee farming.</p>
                </div>
            </div>
        </div>
    </div>
    
</div>