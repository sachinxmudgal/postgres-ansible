@Library('postgres-shared-lib') _

node {


checkout scm

def config = load 'config.groovy'

postgresPipeline(config)


}

