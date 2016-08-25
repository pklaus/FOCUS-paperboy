## Tagesspiegel-paperboy

FOCUS-paperboy is a command line tool to deliver your FOCUS
electronic issue every week. Its CLI signature is as follows:

    usage: paperboy.py [-h] --user-agent USER_AGENT --output-directory
                       OUTPUT_DIRECTORY --email EMAIL --password PASSWORD
                       [--cookie-file COOKIE_FILE] [--debug]
    
    FOCUS-paperboy delivers your FOCUS e-magazine freshly every week.
    
    optional arguments:
      -h, --help            show this help message and exit
      --user-agent USER_AGENT, -ua USER_AGENT
                            User agent you want paperboy to use.
      --output-directory OUTPUT_DIRECTORY, -o OUTPUT_DIRECTORY
                            Directory to store the PDFs of the downloaded issues.
      --email EMAIL, -e EMAIL
                            Email address of your account at https://focus-
                            epaper.de
      --password PASSWORD, -p PASSWORD
                            Password for your account at https://focus-epaper.de
      --cookie-file COOKIE_FILE, -c COOKIE_FILE
                            File to store the cookies in.
      --debug, -d           Increase verbosity.

It is written for Python 3.x and requires the modules
[requests](https://pypi.python.org/pypi/requests/) and
[beautifulsoup4](https://pypi.python.org/pypi/beautifulsoup4/).

