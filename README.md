# Assignment1-ImageProcessing

% Read image into a workspace variable
*img = imread('pengies.jpeg');

% Display the original image
imshow(img);

% Apply an image processing filter
img_filtered = imfilter(img, 2); % (**) you can change the filter you want to apply

% Display the filtered image
figure, imshow(img_filtered);

% Save the filtered image to a .png file
imwrite(img_filtered, 'filtered_image.png');
