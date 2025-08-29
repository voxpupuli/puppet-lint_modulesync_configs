begin
  require 'github_changelog_generator/task'
  require 'yaml'

  GitHubChangelogGenerator::RakeTask.new :changelog do |config|
    config.header = "# Changelog\n\nAll notable changes to this project will be documented in this file."
    config.exclude_labels = %w{duplicate question invalid wontfix wont-fix skip-changelog github_actions}
    config.user = 'voxpupuli'
    config.project = 'puppet-lint_modulesync_configs'
    config.future_release = YAML.safe_load(File.read('moduleroot/.msync.yml.erb'))['modulesync_config_version']
  end
rescue LoadError
end
