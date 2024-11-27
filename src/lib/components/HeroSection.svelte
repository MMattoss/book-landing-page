<script>
	import Button from "./Button.svelte";

</script>
<section class="hero">
	<div class="hero-showcase text-center bold">
    <header>
      <h1 class="purple">MOVE TO</h1>
      <h1 class="purple mb-s">SPAIN</h1>
      <h4 class="italic semi-bold">
        There's no need to make the same mistakes I made.
      </h4>
    </header>
    <img src="phone_cover.png" alt="" class="phone-cover">
		<img src="book_cover.png" alt="" class="book-cover" />
	</div>

	<div class="hero-text white text-center">
		<h1>THIS BOOK WILL</h1>
		<h1>SAVE YOUR MONEY</h1>
		<h1 class="mb-s">TIME & NERVES</h1>
		<p class="light-grey mb-s">
			I moved to Spain seven years ago. The process was painful and
			difficult. I learned most things the hard way: finding a job,
			getting a visa, calculating my cost of living, choosing an
			apartment. That's why I wrote this e-book, to tell you how I did it.
			No bullshit, no stress.
		</p>
    <Button>Purchase E-book for $10</Button>
	</div>
</section>

<style>
  .hero {
    display: flex;
    height: 100vh;
    overflow: hidden;
  }

  .hero-showcase {
    position: relative;
    width: 50%;
    padding: 100px 0;
    background: linear-gradient(
      135deg,
      #e2cbff,
      #e2cbff 25%,
      #deeaff 50%,
      #ece5ff 75%,
      #927bce
    );
  }

  .hero-text {
    padding: 100px 5%;
    width: 50%;
    background-color: black;
  }

  .book-cover {
    position: absolute;
    width: 45%;
    right: 13%;
    bottom: 0;
    transform: translateY(22%);
  }

  .phone-cover {
    position: absolute;
    width: 25%;
    bottom: 0;
    right: 55%;
    transform: translateY(12%);
  }
</style>
