<script lang="ts">
    import type {Image} from '../../interfaces/image'
    const image:Image = {
        source:"sometimesUsefulBW-min.gif",
        alt:"Sometimes Useful"
    }
</script>
<img src={image.source} alt={image.alt}/>