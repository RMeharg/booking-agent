# Booking Agent

Used for easily adding many pipelines to a Concourse deployment using specific environment settings.

# Configuration

- Add jobs using the template provided in `manifest.yml`
- Modify `settings.yml`
- Book to a Concourse deployment using `fly -t TARGET set-pipeline -p booking-agent -c manifest.yml -l settings.yml`
