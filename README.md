# quick-emoji-pro

`quick-emoji-pro` is a robust npm package designed to streamline text-to-emoji conversion. It offers customizable mappings, various replacement modes, and advanced features suitable for production-grade applications.

## Installation

Install the package via npm:

```bash
npm install quick-emoji-pro


Example:

```jsx
const MyComponent: React.FC = () => {
  const { data, error, loading } = useBasicFetch<Joke>('https://api.icndb.com/jokes/random', 2000);

  if (error) {
    return <p>Error</p>;
  }

  if (loading) {
    return <p>Loading...</p>;
  }

  return (
    <div className="App">
      <h2>Chuck Norris Joke of the day</h2>
      {data && data.value && <p>{data.value.joke}</p>}
    </div>
  );
};
```
