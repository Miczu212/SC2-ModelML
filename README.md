# MODELML
Jest to projekt wykorzystujący biblioteke pythona sc2reader

Celem projektu było stworzenie modelu który byłby w stanie przewidzieć zwycięstwo jednego z graczy na podstawie ilości jednostek jakie posiadają

zostały utworzone dwa modele które różnią się podejściem. 
Jeden Model traktuje gracza jako osobną ceche co sprawia że jest węższy
Drugi model traktuje jednostki obu graczy jako osobne cechy modelu co sprawia że jeden model jest szerszy

W celu użycia modelu należy wczytać plik powtórki z gry starcraft 2, następnie na podstawie tego jak się nauczył będzie próbował przewidzieć zwycięsce w momencie jaki wybierzemy,
oznacza to że gdyby został stworzony system liczący jednostki w czasie rzeczywistym można by użyć tego modelu do próby przewidzenia tego jaki gracz ma w danym momencie przewage

MODELML
This is a project that utilizes the Python library sc2reader.

The goal of the project was to create a model capable of predicting the victory of one of the players based on the number of units they possess.

Two models were developed, each with a different approach. The first model treats each player as a separate feature, making it more narrow. The second model treats the units of both players as separate features, making it broader.

To use the model, you need to load a replay file from StarCraft 2. Based on its training, the model will attempt to predict the winner at a chosen moment in the game. This means that if a system were created to count units in real-time, this model could be used to predict which player has the advantage at any given moment.
