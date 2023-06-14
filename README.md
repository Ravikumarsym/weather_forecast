### **Overview**

Weather app created using the [Open weather map Api](https://openweathermap.org/). This is not supposed to be a production scale application, it is meant to demonstrate the implementation of MVP architecture in Kotlin using following libraries:

    RxJava
    Retrofit

### General flow of data

   - Check if there is cached data present in the internal file, if yes then load the cached data.
   - Retrieve the latitude and longitude of the user.
   - Request data from Weather Api
   - If data received, cache it in internal file and show the updated data to user.
   - If you want particular location weather deatils then use the search engine
   - Forecasting weather through date selection 
   - If error then notify user about it.
   
###  key changes File
  companion object{
        private const val PERMISSION_REQUEST_ACCESS_LOCATION = 100
        const val API_KEY ="Your Api key"
    }
  ```
  
