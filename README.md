# Nyaa-Torrent-Database

Database of 71K (71,642) posts from https://nyaa.sbs site (a mirror of https://nyaa.si). <br>
Used a modified version of NyaaPy(https://github.com/JuanjoSalvador/NyaaPy) to scrape the data. <br>
Each object has the fields: <br>
["title", "category", "uploader", "uploader_profile", "website", "size", "date", "seeders", "leechers", "completed", "hash", "files", "description", "id"] <br>
in that order. <br>
Files is an array of filenames. If the post has more than 100 files, it is truncated to 100 files, with the 100th file being the string "..." (without quotes).
    
