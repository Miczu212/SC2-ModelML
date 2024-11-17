# MODELML
Jest to projekt wykorzystujący biblioteke pythona sc2reader

Celem projektu było stworzenie modelu który byłby w stanie przewidzieć zwycięstwo jednego z graczy na podstawie ilości jednostek jakie posiadają

zostały utworzone dwa modele które różnią się podejściem. 
Jeden Model traktuje gracza jako osobną ceche co sprawia że jest węższy
Drugi model traktuje jednostki obu graczy jako osobne cechy modelu co sprawia że jeden model jest szerszy

W celu użycia modelu należy wczytać plik powtórki z gry starcraft 2, następnie na podstawie tego jak się nauczył będzie próbował przewidzieć zwycięsce w momencie jaki wybierzemy,
oznacza to że gdyby został stworzony system liczący jednostki w czasie rzeczywistym można by użyć tego modelu do próby przewidzenia tego jaki gracz ma w danym momencie przewage