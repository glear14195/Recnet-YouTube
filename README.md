# RecNet YouTube Data Extractor

Requires Python3.*

**How to use?**
1. Give Akshat the email that will be used to fetch YouTube data. (Needs to be added to test users list on the Google API console for free, non-verified access)
2. Clone the repository.
3. Run `pip install -r requirements.txt`
4. Run `python sample.py`
5. The above should redirect you to a Google OAuth page asking for YouTube data's readonly access. Accept this using your YT linked email.
6. This will generate 2 files - `<email>_subscriptions.csv` and `<email>_liked_videos.csv`.
