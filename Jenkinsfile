@Library ('shared-library-nico@devel') _

log.info('este es mi mensaje')



node {
    stage  ('Example') {
        def mybranch = branchesInput.ibranch()
        log.test('.')
        log.info ("El branch es ${mybranch}")
    }
}
