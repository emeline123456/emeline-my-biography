<script>
    import Header from '$lib/Header.svelte';
    import Section from '$lib/Section.svelte';

    let myInfo={
        title: "Info",
        item1: "Emeline",
        item2: 13,
        item3: "Han chiang High School"
    }

    let myHobby={
        title: "Hobby",
        item1: "Swimming",
        item2: "Watch movies",
        item3: "Listen to Music"
    }

    let myPersonality={
        title: "Personality",
        item1: "Quiet",
        item2: "Kind",
        item3: "Humble"
    }

</script>
<Header title={"My Biography"} /> 
<Section {...myInfo} />
<Section {...myHobby} />
<Section {...myPersonality} />