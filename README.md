# OptionsAnalysis

In this repository we create a python script that allow to download option data from yahoo finance in any available instrument, store is a csv file and plot the results. 

The code was taken from this [page](https://www.reddit.com/r/options/comments/gvmluu/thought_id_share_a_project_i_just_finished_3d/?utm_medium=android_app&utm_source=share) which creates the 3D plots. 

Changes to the code:

- [x] Filter by expiration date
- [x] Filter by strike price
- [x] Export to csv file
- [ ] Make the code run faster  


I change the code to be able to also export the data into a csv file, unfortanely the author doesn't have github so I have to store my version of the code as my own.

The code is run in python 3.8

We need to follow the instructions in order to get the option data

We select:
- Ticker symbol
- Type of option
- Moneyness
- Risk free (Usually set at 0.01)
- **Expiration date**
- **Strike Price**

The final results is the greek letters used in options under the [Black-Scholes model](https://en.wikipedia.org/wiki/Greeks_(finance)#Formulas_for_European_option_Greeks)

The final output looks similar to this:
![Output](https://user-images.githubusercontent.com/46135649/144330301-3d983ba4-96e4-400b-ab16-c10b33114b3e.png)



