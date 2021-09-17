# AWS-Rekognition-Face-compare

Lambda to accept a file and do a face compare. I took the existing lambda temaple - Rekognition-python and added a function for face compare - compare_faces(). Triggers off an image upload on S3 and compares the image to a template image.

Assumed use case is you are tring to identify a specific person in an image
