# frozen_string_literal: true

source 'https://supermarket.chef.io'
source "https://api.berkshelf.com"
solver :ruby, :required

metadata

group :integration do
  cookbook 'opsworks_ruby'
  cookbook 'apt'
  cookbook 'nginx', git: 'https://github.com/positronicninja/chef_nginx_templates.git'
  cookbook 'ohai'
  cookbook 'yum-epel'
  cookbook 'zypper'
  cookbook 's3fs', '~> 3.0.4', git: 'https://github.com/twilson63/s3fs-recipe.git'
  cookbook 'opsworks-rails-precompile', git: 'https://github.com/positronicninja/opsworks-rails-precompile.git'
  cookbook 'opsworks-cookbook-custom-env', git: 'https://github.com/diegodurante/opsworks-cookbook-custom-env.git'
  cookbook 'opsworks_delayed_job', git: 'https://github.com/joeyAghion/opsworks_delayed_job.git'
  cookbook 'gnr_whenever', git: 'https://github.com/positronicninja/gnr_whenever.git'
  cookbook 'gnr_authorized_users', git: 'https://github.com/Gryphon-And-Rook-Inc/gnr_authorized_users.git'
  cookbook 'gnr_server_tools', git: 'https://github.com/Gryphon-And-Rook-Inc/gnr_server_tools.git'
  cookbook 'wkhtmltopdf-update', git: 'https://github.com/Gryphon-And-Rook-Inc/wkhtmltopdf-update.git'
  cookbook 'gnr_elasticsearch', git: 'https://github.com/positronicninja/gnr_elasticsearch.git'
  cookbook 'unicorn', git: 'https://github.com/positronicninja/chef_unicorn_templates.git'
end