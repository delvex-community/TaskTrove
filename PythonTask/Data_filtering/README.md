
## Using Given API to get the Random data and do the needful 

<details>
 <summary>unlock</summary>
<p>

```bash
> Write python file named datarandom.py .
> In python code call the API ("https://randomuser.me/api/") using any python module you know.
> i am giving a sample example below .
import requests
response = requests.get("https://randomuser.me/api/")
response.json()
> response.json() will give you lots of data in dictonary format 
> you need to print all the info line by line in the gap of 1 second
> info thats needs to be printed line by line 
* Name , Gender , Firstname , lastname , Dob   (line1)
* Country , state , city , postcode  (line2)
* Username , password , email   (line3)

```

</p>
</details>