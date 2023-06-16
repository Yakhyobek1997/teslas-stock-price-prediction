# teslas-stock-price-is-prediction
Tesla's stock price is forecasted over several months by employing an LSTM (Long Short-Term Memory) model. To enhance the accuracy of the predictions, tweets pertaining to Tesla are utilized.

Initially, the LSTM Multivariate Time-Series Prediction model is employed to anticipate the stock price over a specified timeframe. Subsequently, the tweets discussing Tesla are processed to ensure their cleanliness, and their average sentiment scores are computed using TextBlob. Lastly, these daily average sentiment scores are integrated as a feature in the LSTM model and utilized for the prediction process.
