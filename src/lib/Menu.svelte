<script lang="ts">

</script>

<div class="bottom">
<div class="menu">
    <div class="item">
        <button>집</button>
        <p class="pinkify">Home</p>
    </div>
    <div class="item">
        <!-- 생활 a translation of life/living/subsistence -->
        <button>뇌</button>
        <p class="pinkify">Meditations</p>
    </div>
    <div class="item">
        <!-- sinjo 신조 = belief/creed -->
        <button>말</button>
        <p class="pinkify">Quotes</p>
    </div>
    <div class="item">
        <button>시작</button>
        <p class="pinkify">Play</p>
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
		border-radius: 1em;
		outline: white;
        border: 2px white solid;
		font-variant-numeric: tabular-nums;
	}

	button:hover {
		color: pink;
		border: 2px solid hotpink;
		background-color: rgba(0, 0, 0, 0.1);
		
	}

	button:active {
		background-color: rgba(255, 62, 0, 0.2);
	}
    p {
        font-size: x-large;
        padding: 0;
        margin: 0;
    }
    .bottom {
        width: 95%;
        position: absolute;
        bottom: 0;
    }
</style>