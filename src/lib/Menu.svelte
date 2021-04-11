<script lang="ts">

</script>

<div class="bottom">
    <hr>
    <div class="menu">
        <div class="item">
            <button>집</button>
            <p class="pinkify">home</p>
        </div>
        <div class="item">
            <!-- 생활 a translation of life/living/subsistence -->
            <button>뇌</button>
            <p class="pinkify">daily</p>
        </div>
        <div class="item">
            <!-- sinjo 신조 = belief/creed -->
            <button>말</button>
            <p class="pinkify">quotes</p>
        </div>
        <div class="item">
            <button>시작</button>
            <p class="pinkify">play</p>
        </div>
    </div>
</div>

<style>

.menu {
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    align-items: center;
    justify-content: space-around;
    width: 100vw;
   
}
.item {
    width: 20%;
    /* margin: 5px; */
    /* width: 25vw; */

}

button {
		font-family: inherit;
		font-size: 1.5em;
		color: pink;
		background-color: black;
        width: 90%;
        border: 1px white;
	}

	button:hover {
		color: white;
		background-color: rgba(0, 0, 0, 0.1);
		
	}

	button:active {
		background-color: rgba(255, 62, 0, 0.2);
	}
    p {
        padding: 0;
        margin: 0;
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