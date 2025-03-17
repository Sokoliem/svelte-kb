<script>
      import { goto } from '$app/navigation';
    </script>

    <nav>
      <ul>
        <li><a href="/" on:click|preventDefault={() => goto('/')}>Home</a></li>
        <li><a href="/about" on:click|preventDefault={() => goto('/about')}>About</a></li>
        <li><a href="/contact" on:click|preventDefault={() => goto('/contact')}>Contact</a></li>
      </ul>
    </nav>
