# APNsPusher: Push notification via .p8 by Python
----
APNsPusher is a Python version of APNs caller.

# Requirements
----
- Python 3.6 ( I do not sure how about Python 2.7 )
- cryptography
- pyjwt
- hyper

# Installation
----
Put your .p8 file to this folder, then

    pip install -r requirement.txt


# Uage
----
replace `apns.py`

1. `apns_key_id`
2. `apns_key_name`
3. `team_id`
4. `bundle_id`

then run `Python`

	from apns import APNsPusher
	APNsPusher().push("Test Title", "Test Body", "device token", IS_PRODUCTION)

# 繁體中文相關內容介紹

- [APNs - Archie](https://www.archie.tw/apns)