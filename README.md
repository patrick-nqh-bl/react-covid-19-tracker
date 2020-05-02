# Patrick's Project(using React-Hooks, Material UI, Charts JS)

1. Re-code by me:

- Source video:
  > https://www.youtube.com/watch?v=khJlrj3Y6Ls

##### Thank to JavaScript Mastery Youtube channel

- Link deployed on Netlify:
  > https://mystifying-nightingale-4628e1.netlify.app/

2. New npm module:

- classnames
- react-chartjs-2
- react-countup
- chart.js

3. Awesome function:

- Fetch data and modified data

      export const fetchData = async () => {
        try {
          const {
            data: { confirmed, recovered, deaths, lastUpdate },
          } = await axios.get(url);

          return { confirmed, recovered, deaths, lastUpdate };
        } catch (error) {}
      };
