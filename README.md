# Air Quality Prediction in Moroccan Cities

Notebook-based exploration of air-quality data for Moroccan cities. The project covers data collection, cleaning, exploratory analysis, supervised prediction, model evaluation, and a federated-learning simulation that treats cities as separate data partitions.

## Notebooks

- `Air Quality Prediction in Moroccan Cities.ipynb` fetches weather and air-pollution observations, prepares features, trains regression models, and evaluates their predictions.
- `Data_Mining_2.ipynb` explores a broader workflow with data preparation, EDA, model comparison, feature importance, and simulated federated training.

The notebooks use pandas, NumPy, Matplotlib, Seaborn, scikit-learn, and `requests`. A Jupyter environment is also required.

## API key

The live collection notebook reads its OpenWeatherMap credential from the `OPENWEATHERMAP_API_KEY` environment variable. Set it before starting Jupyter; do not paste API keys into notebook cells or commit them.

PowerShell example:

```powershell
$env:OPENWEATHERMAP_API_KEY = "your-key"
jupyter lab
```

## Run

Install the dependencies and open either notebook in Jupyter. The live-data notebook requires API access; `Data_Mining_2.ipynb` also includes a simulated-data workflow.

## Data and outputs

Collected datasets, notebook outputs, and generated charts are excluded from the public repository.
