# Getting Started with Create React App

<h2>Instalação das dependências do gráfico.</h2>

`npm install chartjs`
`npm install react-chartjs-2`

` const [userData, setUserData] = useState({
    labels: UserData.map((data) => data.name),
    datasets: [
      {
        label: "Users Gained",
        data: UserData.map((data) => data.votos),
        backgroundColor: [
          "rgba(75,192,192,1)",
          "#ecf0f1",
          "#50AF95",
          "#f3ba2f",
          "#2a71d0",
        ],
        borderColor: "black",
        borderWidth: 2,
      },
    ],
  });`

`<div className="App">
    <div style={{ width: 700 }}>
    <BarChart chartData={userData} />
    </div>
    <div style={{ width: 700 }}>
    <LineChart chartData={userData} />
    </div>
    <div style={{ width: 700 }}>
    <PieChart chartData={userData} />
    </div>
</div>
`


