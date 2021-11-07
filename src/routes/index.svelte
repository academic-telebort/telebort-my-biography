<script>
    import Header from '$lib/Header.svelte';
    import Section from '$lib/Section.svelte';

    let myInfo = {
        title:"Info",
        item1:"Naz",
        item2:15,
        item3:"MBS"
    }

    let myHobby = {
        title:"Hobby",
        item1:"Playing games",
        item2:"Reading books",
        item3:"Play badminton"
    }
</script>

<Header title={"My Biography"} />
<Section {...myInfo} />
<Section {...myHobby} />
