RAILS_VERSIONS = %w(
  3.0.5
  3.0.6
  3.0.7
  3.0.8
  3.0.9
  3.0.10
  3.0.11
  3.0.12
  3.0.13
  3.0.14
  3.0.15
  3.0.16
  3.0.17
  3.0.18
  3.0.19
  3.0.20
  3.1.0
  3.1.2
  3.1.3
  3.1.4
  3.1.5
  3.1.6
  3.1.7
  3.1.8
  3.1.9
  3.1.10
  3.1.11
  3.1.12
  3.2.0
  3.2.1
  3.2.2
  3.2.3
  3.2.4
  3.2.5
  3.2.6
  3.2.7
  3.2.8
  3.2.9
  3.2.10
  3.2.11
  3.2.12
  3.2.13
  3.2.14
  3.2.15
  3.2.16
  3.2.17
  3.2.18
  3.2.19
  3.2.20
  3.2.21
  3.2.22
  3.2.22.1
  3.2.22.2
  4.0.0
  4.0.1
  4.0.2
  4.0.3
  4.0.4
  4.0.5
  4.0.6
  4.0.7
  4.0.8
  4.0.9
  4.0.10
  4.0.11
  4.0.11.1
  4.0.12
  4.0.13
  4.1.0
  4.1.1
  4.1.2
  4.1.3
  4.1.4
  4.1.5
  4.1.6
  4.1.7
  4.1.7.1
  4.1.8
  4.1.9
  4.1.10
  4.1.11
  4.1.12
  4.1.13
  4.1.14
  4.1.14.1
  4.1.14.2
  4.1.15
  4.2.0
  4.2.1
  4.2.2
  4.2.3
  4.2.4
  4.2.5
  4.2.5.1
  4.2.5.2
  4.2.6
  4.2.7
  4.2.7.1
  5.0.0
  5.0.0.1
)

RAILS_VERSIONS.each do |version|
  appraise "rails_#{version}" do
    gem 'activerecord', version

    if version =~ /^3/
      gem 'minitest', '~> 4.0'
    end
  end
end
