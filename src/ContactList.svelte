<script>
  import contacts from "./src/contacts";
</script>

<div id="contactList">
  {#each $contacts as contact}
    <p>{contact.name} {contact.surname}</p>
    <p>{contact.mail}</p>
    <hr />
  {/each}
</div>
