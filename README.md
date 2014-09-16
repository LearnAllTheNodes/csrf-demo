# CSRF Demo

## Purpose

This is a toy page thrown up to demonstrate how a cross-site request forgery attack would work.  It was made for a Learn All The Nodes episode, and you can see that episode at [http://www.learnallthenodes.com/episodes/34-anatomy-of-a-cross-site-request-forgery-attack](http://www.learnallthenodes.com/episodes/34-anatomy-of-a-cross-site-request-forgery-attack).

Please make sure to protect your site from easy attacks like this!

## How it works

In the episode, this page was served from totallylegitforum.com (not that I own the domain-- hooray for /etc/hosts).  

This page includes an image whose source hits a dangerously-exposed action and also provides a form that tries to hit the same action.

The episode shows how to lock down these 2 vectors.

## License

MIT
