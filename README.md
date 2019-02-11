# SCSC Pier Data Explorer

Data collection and public download of Schiller Costal Studies Center Pier data at Bowdoin College.

The raw data is stored on an Amazon S3 bucket which also contains this code. This code uses the [AWS S3 API](https://aws.amazon.com/sdk-for-browser/) to fetch the bucket index (XML) and presents it in a [jQuery](https://jquery.com) [DataTable](https://datatables.net).

This repository *does not* contain any data, it only contains the surrounding code to make the data accessible.

This is a fork of the [aws-js-s3-explorer](https://github.com/awslabs/aws-js-s3-explorer) example with some minor modifications to work for our purposes. The remainder of the original `README.md` has been removed to avoid any confusion. Please refer to the [original source](https://github.com/awslabs/aws-js-s3-explorer) for more details.
