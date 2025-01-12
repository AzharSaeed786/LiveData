# LiveData
LiveData Kotlin mein ek lifecycle-aware data holder class hai jo observable hai. Iska matlab hai ki yeh data ko observe kar sakti hai aur jab bhi data mein koi change hota hai, to automatically us change ko update kar deti hai. LiveData ko commonly Android app development mein use kiya jata hai, khas taur par ViewModel ke sath, taaki UI components ko lifecycle-aware data updates mil sakein.

LiveData ka main faida yeh hai ki yeh lifecycle ko dhyan mein rakhkar data ko observe karti hai. Agar koi observer (like Activity or Fragment) active state mein nahi hai (jaise onStop ya onDestroy state mein hai), to LiveData updates ko ignore karti hai, isse memory leaks aur crashes ka risk kam ho jata hai
