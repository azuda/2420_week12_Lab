# ACIT 2420 Week 12 Lab

## Repository

### Team Members

  - *Munib Javed A01221306*
  - *Aaron Zhang A01316218*

### File Structure

![file_structure](images/file_structure.png)

## Step 1

Install nginx:

![nginx_install](images/nginx_install.png)

## Step 2

Create **index.html**:

![create_index](images/create_index.png)

Write something to serve in index.html:

![index_html](images/index_html.png)

## Step 3

Create nginx server block file, and write the server block:

![create_sb](images/create_sb.png)

![sb](images/sb.png)

**Note**: replace the IP addresses shown here with your site domain.

## Step 4

Upload the files from steps 2 and 3 to your server (we used sftp here):

![sftp](images/sftp.png)

Move the server block file to `/etc/nginx/sites-available` and ensure `index.html` is in the root directory:

![server_locations](images/server_locations.png)

Create new soft link to server block, test nginx configuration, and restart nginx service:

![s_link](images/s_link.png)

## Step 5

Restart the nginx service:

![nginx_restart](images/nginx_restart.png)

## Step 6


