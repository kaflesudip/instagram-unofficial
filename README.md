# instagram-unofficial
An official Instagram API that enables likes, posts and comments.

## Register the API
    from selenium import webdriver

    username = "Your Instagram Username"
    password = "Your Instagram Password"

    driver = webdriver.Firefox()
    api = register_driver(driver=driver, username=username, password=password)

## Post, Like, Follow, Unfollow
    
    api.unfollow_user(user_id)  # unfollows user with given id.
    api.follow_user(user_id)  # follows user with given id.
    api.create_media_comment(media_id, text)  # Adds the text as comment on the given media id
    api.like_media(media_id)  # Likes the given media
    
    
### Disclaimer
This is an unofficial Instagram bot. Using this may violate Instagram's TOS.
