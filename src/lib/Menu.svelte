<script lang="ts">

</script>

<div class="bottom">
    <div class="menu">
        <div class="item">
            <a href="/">집</a>
            <p class="pinkify">home</p>
        </div>
        <div class="item">
            <!-- 생활 a translation of life/living/subsistence -->
            <a href="/daily">뇌</a>
            <p class="pinkify">daily</p>
        </div>
        <div class="item">
            <!-- sinjo 신조 = belief/creed -->
            <a href="/quotes">말</a>
            <p class="pinkify">quotes</p>
        </div>
        <div class="item">
            <a href="/megaton">시작</a>
            <p class="pinkify">play</p>
        </div>
    </div>
</div>

<style>

.menu {
    font-family: 'Nanum Gothic';
    font-weight: bold;
    text-align: center;
    color: white;
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    align-items: center;
    justify-content: space-around;
    width: 100vw;
   
}
.item {
    width: 20vw;
    /* margin: 5px; */
    /* width: 25vw; */
    border: 2px white solid;
    border-top: none;
    border-bottom: none;
    border-right: none;
    border-top-left-radius: 15%;
    border-bottom-left-radius: 15%;
    border-left-style: dotted;
}

    a {
		font-size: 1.5em;
		color: pink;
		background-color: black;
        border: black none;
	}

	a:hover {
		color: white;
		background-color: rgba(0, 0, 0, 0.1);
		
	}

	a:active {
		background-color: rgba(255, 62, 0, 0.2);
	}
    p {
        padding: 0;
        margin: 0;
        font-weight: lighter;
    }
    .bottom {
        /* position: absolute; */
        position: fixed;
        bottom: 10px;
        margin: 0 0 0 0;
        padding: 0 0 0 0;
        background-color: black;
    }
</style>