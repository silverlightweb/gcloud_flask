# Google Cloud Platform  gcloud_flask
***

1.  command to check your current project:
```bash
  gcloud config list
```
2.  To list existing configurations, run:
```bash
  gcloud config configurations list
```
3.  Set project for gcloud sdk 
```bash
  gcloud project set <your-project-name>
```
4. Display a list box of your project
```bash
  gcloud projects list --format="table[box](name:sort=1:reverse, createTime.date('%d-%m-%Y'))"
```
5. To create a project, run:
```bash
gcloud projects create <ENTER-PROJECT-ID>
```

