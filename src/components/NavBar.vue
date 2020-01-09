<template>
        <nav class="navbar navbar-expand-lg fixed-top navbar-light bg-light">
            <div class="container">
                <span class="navbar-brand mb-0 h1">RAGHAVENDRA ACHARI</span>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse justify-content-end" id="navbarNavAltMarkup">
                    <div class="navbar-nav">
                        <a class="nav-item nav-link  active" href="#">Info</a>
                        <a class="nav-item nav-link" href="#">Till Now</a>
                        <a class="nav-item nav-link" href="#">Skills</a>
                        <a class="nav-item nav-link" href="#">Work</a>
                        <a class="nav-item nav-link" href="#">Contact</a>
                    </div>
                </div>
            </div>
        </nav>
</template>

<script>
export default {
    name:"NavBar"
}
</script>
<style scoped lang="css">
    .navbar{
        box-shadow: 0px 1px rgba(192, 192, 192, 0.623);
    }
</style>
