<script>
  import PostList from '@/components/PostList.svelte'

  import {posts} from '@/posts'
</script>

<svelte:head>
  <title>Hashes</title>
</svelte:head>

<style>
  #callout {
    text-align: center;
  }

  img {
    height: 200px;
  }
</style>

<section id="callout">
  <h1 mx="10" my="9">Publish audio convos. With ease.</h1>
  <h2 mx="10" my="9"> Structured conversations. Better broadcasts.</h2>
</section>

<ul grid columns="2" gap="6" my="9">
  <li cell>
    <h3>Your Hash</h3>
    <p>Grow your channels, together or alone. Hashes are the place where communities gather.</p>
  </li>
  <li cell>
    <h3>Moderated Methods</h3>
    <p>Pass the mic, time-box speakers, audience seats and private mode. Hosting is an art.</p>
  </li>
  <li cell>
    <h3>Publishing Calendar</h3>
    <p>Let your listeners know when you'll be live. Or let them listen to an aired broadcast.</p>
  </li>
  <li cell>
    <h3>Blazing Fast</h3>
    <p>Our 100% native iOS application and audio compression means no lag, ever.</p>
  </li>
  <li cell>
    <h3>Publish Extensions</h3>
    <p>Take your conversations wherever you like. Your archive is entirely yours.</p>
  </li>
  <li cell>
    <h3>Speaker Timeline</h3>
    <p>Moderation means fewer awkward interruptions. Plus we always capture the active speaker.</p>
  </li>
  <li cell>
    <h3>Annotation Markers</h3>
    <p>Revisit your chat and add transcripts, references or markers for all audiences to follow along.</p>
  </li>
  <li cell>
    <h3>One Shots</h3>
    <p>Add one shots from our audio library to bring your chats to life. We also support sponsored ads.</p>
  </li>
  <li cell>
    <h3>Growing Listeners</h3>
    <p>Nurture a personal audience or grow a hash together with multiple hosts. Build your following.</p>
  </li>
  <li cell>
    <h3>Verified Accounts</h3>
    <p>We follow a strict usage policy to keep trolls out. No more anonymous interactions.</p>
  </li>
</ul>

<section my="9" id="callout">
  <img src="logo.svg" alt="logo">
  <h2>We're more than a chat room.</h2>
  <button>Get on the waitlist</button>
</section>
<!-- <PostList {posts}/> -->