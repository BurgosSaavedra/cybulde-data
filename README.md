# cybulde-data
Utilizing Data Version Control (DVC) for effective data versioning.
## Installing
1. Create your bucket and compute engine instance.
2. Install git, make, docker, docker-compose.
3. Download as ZIP in the instance.
4. Upload in the instance.
5. Create a new repository in GitHub for managing the data version.
6. Connect to your new repository in GitHub.
7. Connect SSH GitHub in your instance.
8. Change your remote URL from HTTPS to SSH.
9. Push your local repository to your new repository in GitHub.
10. ./blueprint/config_schemas/config_schema.py: Modify bucket name.
11. ./docker/Dockerfile: Modify your git information.
12. Run: make lock-dependencies
13. Move your first data to ./data/raw
14. Run: make version-data
15. Review in your new GitHub repository if it was loaded correctly.
