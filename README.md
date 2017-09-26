# CS310
Project Paper

```cpp
/*
	Input Temperature Function
*/
void setWeatherStation() {
	bool correctWeatherStationInput = false;
	cout << "--- Anthony Hamill Weather Station Application ---" << endl;
	while (!correctWeatherStationInput) {
		cout << "Please enter weather station name: ";
		getline(cin, input);
		if (input.length() == 0) {
			cout << "Not valid input! The input must not be empty." << endl;
		} else {
			stringstream(input) >> weatherStation;
			correctWeatherStationInput = true;
		}
	}
}
```
