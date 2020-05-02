# Patrick's Project(using React-Hooks, Material UI, Charts JS)

2. New npm module:

- classnames
- react-chartjs-2
- react-countup

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
