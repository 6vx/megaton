<script lang="ts">

</script>

<div class="bottom">
    <div class="menu">
        <div class="item">
            <button>집</button>
            <p class="pinkify">home</p>
        </div>
        <div class="item">
            <!-- 생활 a translation of life/living/subsistence -->
            <button>뇌</button>
            <p class="pinkify">meditations</p>
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
}
.item {
    min-width: 75px;
    margin: 5px;
}

button {
		font-family: inherit;
		font-size: 2em;
		color: pink;
		background-color: black;
		font-variant-numeric: tabular-nums;
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
        position: absolute;
        width: 95vw;
        bottom: 10px;
        overflow: auto;
    }
</style>