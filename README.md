# My Spotify Wrapped to Google Sheets 📈

Ever wondered how to keep track of your top Spotify tracks in a cool and organized way? I did, and that's why I built this fun mini project! It takes my favorite Spotify tunes and neatly logs them into a Google Sheet. 📊✨

## What I Did

I embarked on a musical journey using Python, diving into the Spotify API to fetch my top tracks. Using the powerful `spotipy` library, I seamlessly authorized access to my Spotify data, ensuring I could retrieve the crème de la crème of my music preferences.

Once I had my top tracks, I didn't stop there! I extracted detailed features of each song, from the catchy names to the fabulous album covers. This data was then formatted into a beautiful pandas DataFrame.

But I wanted to do more than just print this data on my screen. I harnessed the magic of Google Sheets by utilizing the `gspread` library. With a bit of authorization wizardry using a service account, I securely connected to my Google Sheet and created a dynamic way to store my musical insights.

I didn’t just capture my current top tracks, but also categorized them based on time ranges: short-term, medium-term, and long-term favorites. This allowed me to create separate tabs in my Google Sheet for each category, providing a comprehensive view of my evolving musical tastes.

## The Result

A well-organized Google Sheet that keeps a record of my top Spotify tracks, complete with album names, artists, Spotify URLs, and album covers. Now, I can easily track how my music taste changes over time and share it with friends!


