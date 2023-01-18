# Assignment1-ImageProcessing

% Read image into a workspace variable
*img = imread('pengies.jpeg');*
&nbsp;
% Display the original image
imshow(img);
&nbsp;
% Apply an image processing filter
img_filtered = imfilter(img, 2); % (**) you can change the filter you want to apply
&nbsp;
% Display the filtered image
figure, imshow(img_filtered);
&nbsp;
% Save the filtered image to a .png file
imwrite(img_filtered, 'filtered_image.png');
