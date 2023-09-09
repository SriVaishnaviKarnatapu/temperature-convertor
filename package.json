const convertCtoFButton = document.getElementById("convertCtoF");
const resultCtoF = document.getElementById("resultCtoF");

convertCtoFButton.addEventListener("click", () => {
  const celsiusInput = document.getElementById("celsius").value;
  const fahrenheit = (celsiusInput * 9) / 5 + 32;
  resultCtoF.textContent = `${celsiusInput}°C is ${fahrenheit.toFixed(2)}°F`;
});

const convertFtoCButton = document.getElementById("convertFtoC");
const resultFtoC = document.getElementById("resultFtoC");

convertFtoCButton.addEventListener("click", () => {
  const fahrenheitInput = document.getElementById("fahrenheit").value;
  const celsius = ((fahrenheitInput - 32) * 5) / 9;
  resultFtoC.textContent = `${fahrenheitInput}°F is ${celsius.toFixed(2)}°C`;
});
