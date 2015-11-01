# net-poetry
### Description
This python script takes in a text file as parameter and for each word in that file, it fetches the google auto suggestion for that word and saves it to a text file with the date added to the name as well as printing it out in the terminal. I use it to create meta-poetry from old poetry, feel free to use this for whatever purposes.

### Usage
`python google-suggestions textfile`

### Other information
* This script tries to get unique suggestions for repeated words. The Google suggestion API returns 4 suggestions for each word (if it can), so when a word appears more often than that, the script adds a space after the word to get more suggestions
* The google suggestion api uses the IP-address from your computer, so if you wanna see auto suggestions from another country you need to vpn from a location in that country.

### Poem Example
Original text: http://www.songlyrics.com/mark-kozelek-jimmy-lavalle/gustavo-lyrics/

My poem, inspired from the output from this script:
http://beggab00.tumblr.com/post/125461160794/the-tale-of-gustavo


