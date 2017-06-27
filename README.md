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

    pip install -r requirement.txt

# Uage
----

	from apns import APNsPusher
	APNsPusher().push("Test Title", "Test Body", "device token", IS_PRODUCTION)

