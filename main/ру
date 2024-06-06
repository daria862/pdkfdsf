import requests

def get_random_joke():
    url = "https://api.chucknorris.io/jokes/random"
    response = requests.get(url)
    if response.status_code == 200:
        joke = response.json()['value']
        return joke
    else:
        return "Failed to fetch joke"

print(get_random_joke())
