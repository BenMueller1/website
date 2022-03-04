<template>
<div id="subscribe-div">
    <h3 id="subscribeTitle"> Keep in touch </h3>
        <form action="https://hackwashu.us14.list-manage.com/subscribe/post" method="POST" id="subscribe">
            <input type="hidden" name="u" value="d6407a071d93443bbb9a61e1c">
            <input type="hidden" name="id" value="a3154e19e4">
            <input type="email" autocapitalize="off" autocorrect="off" name="MERGE0" id="MERGE0" size="25" value="">
            <div id="submitGroup">
                <input type="submit" class="formEmailButton" name="submit" value="Subscribe">
            </div>
        </form>
</div>
</template>

<script>
export default {
    name: 'Form'
}
</script>

<style scoped>

#MERGE0 {
    width:90%;
}

#subscribe {
    /* margin: 8px 0; */
    border: 2px solid var(--orange);
}

#subscribe-div {
    color: rgb(255, 255, 255);
    justify-content: center;
    text-align: center;
    margin: auto;
    width:50%;
    line-height: 2;
    font-family: Mont;
}

</style>
