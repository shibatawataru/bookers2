<%= form_with model: List.new do |f| %>
  <h4>Title</h4>
  <%= f.text_field :title %>
	
  <h4>Opinion</h4>
  <%= f.text_area :body %>
	
  <%= f.submit 'Create Book' %>
<% end %>