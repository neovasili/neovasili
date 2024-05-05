# Hi, I'm Juan 👋

<img align="right" width="250" height="250" style="padding: 2rem;" src="assets/img/my-octocat.png?raw=true">

I am Juan Manuel Ruiz Fernández, a.k.a. *neovasili*, born in Malaga and based in the amazing city of Cáceres, now working as a Software and Cloud Engineer but I've played several roles around the cloud engineering, web development, DevOps, infrastructure, serverless and AWS ☁️.

Polyglot programmer, and neverending student in the continuous search of excellence on delivering value. Always trying to help people to go together, share success and learn from mistakes. Smart humor and enjoyment with my job is a must. Very proactive, hungry for new knowledge and always trying to get the best of myself.

-*I know many things, but I ignore many more.*-

## 💻 Me as code

```python
class NeoVasili(Human):
  def __init__(self) -> None:
    self.full_name = "Juan Manuel Ruiz Fernández"
    self.description = """
      Born to code. Cloud Engineer. IaC. Serverless developer. AWS necromancer
      Feel the metal inside you 🤘🤘🤘
    """
    self.website = "https://linktr.ee/neovasili"
    self.job_role = "Cloud Engineer"
    self.music = ["metal", "rock"]
    self.sports = ["mountain bike", "crossfit", "scuba diving", "tennis", "f1"]
    self.hobbies = ["lego", "videogames", "travel"]
    self.languages = ["spanish", "english"]
    self.skills = {
      "soft": [
        "proactive",
        "empathic",
        "challenges lover",
        "accountability",
        "team spirit",
        "perseverant",
        "collaborative",
        "lead by example",
        "continuous learning",
        "automation first mindset",
        "architecture",
      ],
      "tech": TechSkillSet(
        cloud=[
          TechCloudSkillSet(
            name="AWS",
            most_used_services=[
              "IAM", , "S3", "CloudFormation",
              "Route53", "CloudFront", "CodeBuild", "Lambda", "Step functions", "API Gateway", "DynamoDB",
              "SSM", "Secrets manager", "KMS",
              "EC2", "RDS", "VPC", "ECS / ECR / EKS",
              "SQS", "EventBridge", "SNS",
            ],
            other=["AWS cli", "boto3"],
          ),
          TechCloudSkillSet(
            name="Azure",
            most_used_services=[
              "Azure Active Directory",
              "Azure DevOps",
            ],
          ),
        ],
        general_tooling=["git", "shell scripting"],
        most_used_languages=[
          InterpretedProgrammingLanguage(name="python"),
          InterpretedProgrammingLanguage(name="typescript"),
          CompiledProgrammingLanguage(name="golang"),
          CompiledProgrammingLanguage(name="rust"),
        ],
        most_used_frameworks=["CDK", "serverless framework", "terraform", "pulumi"],
        containers=["docker", "kubernetes"],
      ),
    }
    self.certifications = [
      "AWS Solutions Architect Associate",
      "AWS DevOps Engineer Professional",
      "AWS Security Speciality",
    ]
    self.tags = ["aws", "cloud", "serverless", "iac", "architecture"]
```

## 🔉 Talks

Sometimes I speak at conferences and meetups.

- (CDK Day 2023) [Inter-stack dependencies strategies in CDK](https://www.cdkday.com/#inter-stack-dependencies-strategies-in-cdk) ([slides](https://files.juanmanuelruizfernandez.com/speechs/inter-stacks-dependencies-strategies.pdf), [repo](https://github.com/neovasili/cdk-day-2023-stacks-dependencies), [blog post](https://dev.to/aws-espanol/estrategias-para-manejar-dependencias-entre-stacks-en-cdk-3bjj) - spanish, [video](https://www.youtube.com/watch?v=ZAQC-cOXL4M&t=7730s) - spanish)
- (CaceresTech 2023) [101 Rust](https://www.meetup.com/es-ES/cacerestech/events/292010650/) ([slides](https://files.juanmanuelruizfernandez.com/speechs/101-rust.pdf), [repo](https://github.com/neovasili/101-rust))
- (EDD 2022) [Modern Infrastructure as Code](https://extremaduradigitalday.com/ponente/juan-manuel-ruiz-fernandez/) ([slides](https://files.juanmanuelruizfernandez.com/speechs/modern-infrastructure-as-code.pdf), [video](https://www.youtube.com/watch?v=SGXoqiVTG_o) - spanish)
- (s|ngular Hub Madrid 2019) [101 - Serverless framework](https://twitter.com/sngular/status/1194671450793357313)
- (EDD 2019) [101 - Serverless framework](https://2019.extremaduradigitalday.com/ponente/juan-manuel-ruiz-fernandezsngular/)
- (EDD 2018) [Lambda, S3, DynamoDB. Welcome to the AWS serverless world](https://2018.extremaduradigitalday.com/ponentes/juan-manuel-ruiz-fernandez/) ([video](https://youtu.be/VO2_3wuaNBk?t=7110) - spanish)
- (Caceres DevOps 2018) [Serverless & devops with AWS. Theory of everything](https://www.meetup.com/es/caceres-devops/events/254786282/)
