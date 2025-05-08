chưa sử dụng helm
đã up đc image lên google cloud nhưng thiếu resource file( cái file liên quan đén cluster và k8s hay sao). trong github action ở đoạn upload to gke trong file build and deploy.yaml 
nếu như mấy ông muốn thử thì file  build and deploy.yaml không cần chỉnh. thứ cần chỉnh là secret key của phần setting có 2 cái là GOOGLE_APPLICATION_CREDENTIALS, GOOGLE_PROJECT. GOOGLE_PROJECT là ID của project còn GOOGLE_APPLICATION_CREDENTIALS thì ông copy full content của file erpnext-ptuddn-454813-735e8b4c4d6d.json trong phần value.

giờ bận quá :(((
