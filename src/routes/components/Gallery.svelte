<script lang="ts">

    

    const images = [
        { src: 'src/lib/images/Father and son.jpg', alt: 'A father, smiling, holding his infant son' , title: 'Father and Son' },
        { src: 'src/lib/images/Mother.jpg', alt: 'A young black woman posing in a headshot' , title: 'Mother' },
        { src: 'src/lib/images/Siblings.jpg', alt: 'A portrait of a young man holding his infant brother' , title: 'Siblings' },
        { src: 'src/lib/images/Sister.jpg', alt: 'A portrait of a young black woman with locs smiling' , title: 'Sister' },
        { src: 'src/lib/images/Madi.jpg', alt: 'A young woman in a white tee and black shorts posing with one hand behind her head' , title: 'Madi' },
        { src: 'src/lib/images/Boss lady.jpg', alt: 'A confident woman in a work polo' , title: 'Boss Lady' },
        { src: 'src/lib/images/Dad as a kid.jpg', alt: 'A young boy posing for a portrait' , title: 'Dad as a Kid' },
        { src: 'src/lib/images/Afro portrait.jpg', alt: 'A portrait of a black woman with a tall afro' , title: 'Afro Portrait' },
        { src: 'src/lib/images/Grad portrait.jpg', alt: 'A portrait of a young graduate in cap and gown' , title: 'Grad Portrait' },
        { src: 'src/lib/images/Gear 5.jpg', alt: 'From behind, we see a man clad in white clouds looking at the moon with arms outstretched on the battlefield' , title: 'Gear 5' },
        { src: 'src/lib/images/Black Panther cosplay.jpg', alt: 'A portrait of a man in the black panther costume' , title: 'Black Panther Cosplay' },
        { src: 'src/lib/images/Luffy.jpg', alt: 'A portrait of the character Luffy from One Piece' , title: 'Luffy' },
        { src: 'src/lib/images/Zolo_.jpg', alt: 'A portrait of the character Zolo from One Piece' , title: 'Zolo' },
        { src: 'src/lib/images/Sanji_.jpg', alt: 'A portrait of the character Sanji from One Piece' , title: 'Sanji' },
    ]


</script>

<section id="gallery">
    <ul class="columns-3xs">
        {#each images as image(image.title)}
            <li class="my-4">
                <img src={image.src} alt={image.alt} />
            </li>
        {/each}
    </ul>
</section>
