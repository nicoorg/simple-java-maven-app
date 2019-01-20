@Library ('shared-library-nico@devel') _

log.info('este es mi mensaje')

def mybranch = branchesInput.ibranch()

node {
    stage  ('Example') {
        log.test('.')
        log.info ("El branch es ${mybranch}")
    }
}
