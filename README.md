usage: fantiadl.py [options] url

positional arguments:
  url                   fanclub or post URL

options:
  -h, --help            show this help message and exit
  -c SESSION_COOKIE, --cookie SESSION_COOKIE
                        _session_id cookie or cookies.txt
  -q, --quiet           suppress output
  -v, --version         show program's version number and exit

download options:
  -i, --ignore-errors   continue on download errors
  -l #, --limit #       limit the number of posts to process per fanclub (excludes -n)
  -o OUTPUT_PATH, --output-directory OUTPUT_PATH
                        directory to download to
  -s, --use-server-filenames
                        download using server defined filenames
  -r, --mark-incomplete-posts
                        add .incomplete file to post directories that are incomplete
  -m, --dump-metadata   store metadata to file (including fanclub icon, header, and background)
  -x, --parse-for-external-links
                        parse posts for external links
  -t, --download-thumbnail
                        download post thumbnails
  -f, --download-fanclubs
                        download posts from all followed fanclubs
  -p, --download-paid-fanclubs
                        download posts from all fanclubs backed on a paid plan
  -n #, --download-new-posts #
                        download a specified number of new posts from your fanclub timeline
  -d %Y-%m, --download-month %Y-%m
                        download posts only from a specific month, e.g. 2007-08 (excludes -n)
  --exclude EXCLUDE_FILE
                        file containing a list of filenames to exclude from downloading
