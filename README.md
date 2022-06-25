# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
  <div class="form-control">
    <% if @post.image.attached? %>
       <%= image_tag @post.image, style: "width: 200px; display: block" %>
    <% end %>
    <%= form.label :image %>
    <%= form.file_field :image %>
  </div>