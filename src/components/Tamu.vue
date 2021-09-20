<template>
    <div>
        <h2>Form Data Tamu {{myapp}}</h2>
        <form action="" method="post">
            <label for="nama">Nama</label>
            <input type="text" name="nama" id="">
            <label for="subjek">Subjek</label>
            <input type="text" name="subjek" id="">
            <label for="pesan">Pesan</label>
            <input type="text" name="pesan" id="">
            <button type="submit">Submit</button>
        </form>
    </div>
</template>
<style scoped>
form,label{
    display: block;
}
button{
    display: block;
    margin:auto;
    padding:auto;
    width: 13%;
    margin-top: 10px;
}
</style>
<script>
export default {
name: "Tamu",
props: {
myapp: String,
},
};
</script>