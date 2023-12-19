<script>
  import { Deta } from 'deta';
  const deta = Deta("d0dp9wwujge_SQyamf1vWbiC9BVP6m3PB9kj4naCcMJx");
  const db = deta.Base('hero'); 

  let title = "";
  let paragraph = "";

  async function loadData() {
      const data = await db.get('textsBox');
      if (data) {
          title = data.title;
          paragraph = data.paragraph;
      }
  }

  async function saveChanges() {
      await db.put({ key: 'textsBox', title, paragraph });
  }

  loadData();
</script>

<main>
  <h1>Admin Panel</h1>
  <form on:submit|preventDefault={saveChanges}>
      <label for="title">Title:</label>
      <input id="title" type="text" bind:value={title} />

      <label for="paragraph">Paragraph:</label>
      <textarea id="paragraph" bind:value={paragraph}></textarea>

      <button type="submit">Save Changes</button>
  </form>
</main>

<style>
  * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
  }

  main {
      padding: 20px;
      max-width: 600px;
      margin: 0 auto;
      background-color: #f4f4f4;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
  }

  h1 {
      text-align: center;
      color: #333;
      margin-bottom: 20px;
  }

  form {
      display: flex;
      flex-direction: column;
      gap: 15px;
  }

  label {
      font-size: 16px;
      color: #333;
      margin-bottom: 5px;
  }

  input[type="text"], textarea {
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 4px;
      font-size: 14px;
  }

  textarea {
      height: 100px;
      resize: vertical;
  }

  button {
      background-color: #2169ad;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 16px;
      transition: background-color 0.3s;
  }

  button:hover {
      background-color: #1a548b;
  }
</style>
